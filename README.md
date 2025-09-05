<h1>Technicolor-Panoramic-Router-Default-Passwords</h1>
Did this project help you? <a href="https://buymeacoffee.com/rhettrhett1">Buy me a coffee</a>

<h2>About:</h2>
This is a project to create wordlists for Technicolor CGM4331, CGM4141, and CGM4981 default passwords used by Cox, Xfinity, Rogers, etc.<br><br>

For <strong>COX</strong> specifically, SSID will start with 'SETUP-' plus 4 hex like:<br>
"SETUP-1234"<br>
"SETUP-FEDC"<br><br>

For <strong>Xfinity</strong>, SSID will start with 'XFSETUP-' plus 4 alphanumeric + 2 digits in any order like:<br>
"XFSETUP-A3F2"<br>
"XFSETUP-7AE3"<br>
"XFSETUP-6AH4"<br><br>

For <strong>Rogers</strong>, SSID will start with 'EasyConnect' plus 5 random numbers like:<br>
"EasyConnect37821"<br>
"EasyConnect90456"<br><br>

Default Password Breakdown:<br>
A= 5-6 letter word<br>
X= 4 random numbers between 0000-9999<br>
B= 5-6 letter word<br>
Examples:<br>
circle4298empty<br>
chore4982become<br><br>

There is always one 5-letter word and one 6-letter word, but their placements vary. They are always lowercase.<br><br>

Also to note:<br>
From the known passwords I have found, I haven't found any words used starting with letters I-Z. This is why the wordlist only features words starting with A-H.<br>

<h2>Wordlists:</h2>
<h3><b>*Recommended*</b> List1 first:</h3>
-6 letter character word+####+ 5 letter word<br>
-Around 67% chance of success<br>
<h3>List2 second:</h3>
-5 letter character word+####+ 6 letter word<br>

<h2>Hashcat Usage:</h2>
Attack 1: 6letter+digits+5letter (67% success rate)<br>
<code>hashcat -a 1 -m 22000 yourhash.22000 6letter_digits.txt 5letter.txt</code><br><br>
Attack 2: 5letter+digits+6letter (if Attack 1 fails)<br>
<code>hashcat -a 1 -m 22000 yourhash.22000 5letter_digits.txt 6letter.txt</code>
