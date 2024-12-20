# COX-Panoramic-Router-Default-Passwords

<h2>About:</h2>
This is a working project to create wordlists for Cox Panoramic Wifi Routers default passwords.<br>
Please contribute by checking to see if your known passwords are on the list.<br><br>
Default Password Breakdown:<br>
(5-6 letter word)XXXX(5-6 letter word)<br>
From what I've seen, there is always one 5-letter word and one 6-letter word, but their placements vary. They are always lowercase.<br><br>
Also to note:<br>
From the known passwords I have seen, I have never seen a word used that starts after the letter "H".<br>
I would recommend doing the shorter wordlist first (A-H), followed by the big wordlist.

<h2>Usage:</h2>
hashcat -m 22000 -a 1 yourhash.22000 list1.txt.gz list2.txt
