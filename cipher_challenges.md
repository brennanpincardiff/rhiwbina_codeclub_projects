# Welcome to Code Club. 
## Here are two challenges that you can try to learn about ciphers 

### A substitution cipher: Caesar cipher

The easiest place to start is the <b> Caesar cipher </b>. A key number is used to shift the alphabet and change the letters. 

For example the letters "Hello World" are tranformed into "Khoor Zruog" with a shift of three letters. 

``` text
A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
D E F G H I J K L M N O P Q R S T U V W X Y Z A B C
```

Try to decode these messages as practice:

Uklzelqd Frgh Foxe lv juhdw
L oryh vxpphu krolgdbv

You can change the number of letters you shift (sometimes called the ROT number) but this remains an easy cipher to break. 

You can learn more on Khan Academy here: https://www.khanacademy.org/computing/computer-science/cryptography/crypt/v/caesar-cipher

You can learn to programme a Caesar cipher with python here here: https://projects.raspberrypi.org/en/projects/secret-messages/2

This site will encode and decode for you: https://www.dcode.fr/caesar-cipher

Other substitution ciphers:
- Pigpen cipher  try decoding this
<img width="336" alt="Screenshot 2023-07-08 at 14 10 13" src="https://github.com/brennanpincardiff/rhiwbina_codeclub_projects/assets/7151469/dd3fd8dd-60a6-4fba-8787-c6688a20b91a">

  
- Morse code      try decoding this
.-. .... .. .-- -... .. -. .- / .-.. .. -... .-. .- .-. -.-- / .... .- ... / - .... . /
   -... . ... - / -.-. --- -.. . / -.-. .-.. ..- -...


### A transposition cipher: Rail Fence Cipher

A transposition cipher rearranges the letters according to a secret system rather than changing the letters. A simple way would be to
write the letters backwards or mirror writing. 

A example is the <b>Rail Fence Cipher</b>. Also known as a zigzag cipher
The following steps are used:
- Choose text: eg. "I love Rhiwbeina Code Club"
- Write the text on two levels alternating the letters between the top and bottom level. 
``` text
I O E H W E N C D C U 
 L V R I B I A O E L B 
```
- Copy the top rown and then the bottom row 
- This gives
IOEHWENCDCULVRIBIAOELB

To solve, we count the letters (22), divide in two (11)
and then write these out above and below each other to decode. 
``` text
I O E H W E N C D C U 
L V R I B I A O E L B 
```
Then we write out the words again. 

Sometimes we break this into blocks of letters to make it easier to read and we fill up these blocks with dummy letters. 
This would give. 
IO EH WE NC DC UL VR IB IA OE LB

Try to decode these messages as practice:
RI BN CD CU IG ET HW IA OE LB SR A
IO EU MR OI AS LV SM EH LD Y

This site will encode and decode for you: https://www.dcode.fr/rail-fence-cipher

More on transposition ciphers:
- A three rail cipher
Try decoding this...
RBL AAE TEB HWI AIR RHS HBS CDC UIN BYT EOL

- The twisted path cipher
Look up Martin Garnder book and try decoding this:
RI BR NH IA AR LW BI Y  

Remember you can always try this site: https://www.dcode.fr


For puzzles and games (good learning and a bit of fun):
- https://cybergamesuk.com/ 
- Try free puzzles on this page: https://play.cyberstart.com/ (requires registration and futher levels requrie payment)

For some of the theory about cyphers, here is a free educational link from Khan Academy:
- https://www.khanacademy.org/computing/computer-science/cryptography
- https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/the-need-for-encryption

Trial codes are: 
Rhiwbina Code Club is great
I love summer holidays
RHIWBINA LIBRARY HAS THE BEST CODE CLUB
Rhiwbina Library

