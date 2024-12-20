# COX-Panoramic-Router-Default-Passwords

<h2>About:</h2>
This is a working project to create wordlists for Cox Panoramic Wifi Routers default passwords.<br>
Please contribute by checking to see if your known passwords are on the list.<br><br>
Wordlist was created by filtering the most common English words between 5-6 characters from <a href="https://github.com/dolph/dictionary/tree/master">Dolph Github</a><br><br>
SSID will start with 'SETUP-' plus 4 hex like:<br>
"SETUP-1234"<br>
"SETUP-FEDC"<br><br>
Default Password Breakdown:<br>
A= 5-6 letter word<br>
X= 4 random numbers between 0000-9999<br>

(A)XXXX(A)<br>

Examples:<br>
circle4298empty<br>
chore4982become<br><br>

From what I've seen, there is always one 5-letter word and one 6-letter word, but their placements vary. They are always lowercase.<br><br>
Also to note:<br>
From the known passwords I have seen, I have never seen a word used that starting with letters G-Z.<br>
I would recommend doing the shorter wordlist first (A-H), followed by the big wordlist.<br>

<h2>Wordlists:</h2>
<h3><b>*Recommended*</b> Smaller Wordlist (A-H):</h3>
-3082 Words<br>
-69MB compressed<br>
-Tested on Lambda, took less than 2 hours to crack using gpu_8x_a100_80gb_sxm4 (240 CPU cores, 1.9 TB RAM, ~$25 with Cloud GPU)<br>
-Worked on all handshakes I personally tested.<br><br>
<h3>Full Wordlist:</h3>
-7168 Words<br>
-160MB compressed<br>
-Never have had to use. Only recommend using if the smaller wordlist doesn't work.<br>




<h2>Hashcat Usage:</h2>
hashcat -m 22000 -a 1 yourhashfile.hash list1.txt.gz list2.txt<br>
(Do not unzip list1.txt.gz, leave it compressed. Only unzip the wordlist file to get the contents.)
