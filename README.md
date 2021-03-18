# CTF-WriteUp
*This is my CTF challenge practice for codepade class*
![Image of homepg](https://github.com/noiaa990/CTF-WriteUp/blob/ce17d3d419ce397a7234dd65ee0e540992c99559/CTF_Homepage.gif)



**CTF WEEK1**
- **1.01 Zimbabwe - Peculiar Employees**
   - Description
     - Sometimes it's not what you add but what you take away instead
   - Hind
   
- **1.02 Namibia - secre number1**
   - Description
     - Seems like there's a sequence to those numbers, wonder what would happen if you 
       used the next number in the sequence?
   - Hind


- **1.06 Indonesia**
   - Description
     - Three documents: first the riddle, then the answer, then the flag.
   - Hind
   
- **1.07 Canada - secret numer 2** 
   - Description
     - This challenge is looking for a secret number
     - A geometric number series this time, but with a twist at the end: the flag is encoded.
   - Hind
- **1.04 Turkmenistan - Hidden user**
   - Description
     - Another number series? Some engineers love maths.
   - Hind
- **1.11 Egypt - Key player2**
   - Description
     - This time the developer was 'smart' and encoded the param values.
   - Hind
- **1.05 Chad - Odd list**
   - Description
     - One of these lists is not like the others.
   - Hind 
- **1.09 Nigeria - Secret Number 3**
   - Description
     - Here we have a famous number sequence (think: seashells) and an unlinked page with a clue.
   - Hind    
   
   
     
**CTF WEEK2**

 - **Myanmar 2.11 - IDOR1**
   - Description
     - IDOR Flag 1
   - Hind
     - Do nothing with this one
     - Free flag showup 
 - **Iran 2.05 - CSRF5**
   - Description
     - Again with these methods!?
   - Hind
     - Need burp to find a flag (repeater)
     - change GET to POST 
 - **Chile 2.13 - IDOR3**
   - Description
     - What id do I have to set to get a flag around here??
   - Hind
     - Use intruder tool in burp looking for id that will give a flag
 - **United States 2.09 - CSRF9**
   - Description
     - Fine, I'll just mostly do it myself
     - 
   - Hind
     - 
 - **Mexico 2.15 - Sessions2**
   - Description
     - The developer accidentally left a debugging tool available at https://flags.codepath.com/http/public/hacktools/change_session_id.php
   - Hind
     - use burp look for session id and use link that they provide to change it.
     - after session id change, flag will show on web app.
 - **Venezuela 2.07 - CSRF7**
   - Description
     - To change or not to change
   - Hind
     
 
  
**CTF WEEK4**

*This week is about SQL Injection attacks by sending malicious input to a web application.*

 - **Thailand 4.02 - Painless**
   - Description
    - Seems like you are trailing behind and creating a space.
   - Hind
 - **Japan 4.06 - Alternative**
   - Description
    - They say 'when in doubt bet on wildcards.
   - Hind
    - make a list of SQL Injection code and use burp to find it 
    - or manual trype in one by one to to force web app show table of database that keep CTF Flag
 - **Mongolia 4.08 -Gizmo**
   - Description
    - Déjà vu can feel so real it's WILD!
   - Hind
 - **Yemen 4.03 - Logic**
   - Description
     Keep everything close and don't leave any spaces!
   - Hind 
 - **Kenya 4.05 -wild one**
   - Description
     What's yoUR dream job type? I have aLways wanted to be a flag holder. 
     I hope my dream comes true.
   - Hind 
 - **France 4.04 - Censor**
   - Description
     Have you read any interesting comments recently?
   - Hind  
 - **Spain 4.01 - Hello, SQLi**
   - Description
     Sometimes the simplest answer is the true one.
   - Hind
  
  
**CTF WEEK 5**
 - **Colombia 5.08 - Crypto/IDOR**
   - Description
     - The flag is encrypted with a cipher from the ancient world.
   - Hind
     - Needed 2 step to find ctf answer
       - Use IDOR sloving concept looking for user ID by using intruder in burp to get an id 
         and it will show the ancient world that look like ctf format
       - Decode ancient world to text by recommenced tool (http://rumkin.com/tools/cipher/atbash.php)
     
 - **Brazil 5.07 - PROTECK YA NECK**
   - Description
     - The base64-encoded content in the attached file has been encrypted via AES
     - CLUsFeOpcKy9qzeyuqVEuGJwIV9CZep3p/SeqKaQ9JXfl6PEpEE7gInM+mOfdtUi
   - Hind
     - Key is PROTECK YA NECK
     
 - **Congo-Brazzaville 5.03 - Fixed XOR1**
   - Description
    - *CTF{value} where 'value' is the XOR of the following two strings (excluding quotes): 
     '42696c6c792c20646f6e27' and '742062652061206865726f'*
   - Hind
    - 
  
 - **Azerbaijan 5.01 -Decode the flag 1**
   - Description
     - Encode is look like base64
     - KkNURntraWxsaW5nIHlvdXIgYnJhaW4gbGlrZSBhIHBvaXNvbm91cyBtdXNocm9vbX0=
   - Hind
     - This is a stretch challenge and use a decoder tool in burp to decode it.
     
 - **Central African Republic 5.02 - Decode the flag 2**
   - Description
     - 2a4354467b4272696e67204461205275636b75737d
   - Hind
     - Decoding by ool online.
