#### BossMessage

The challenge was a Zip file named `Boss_Message.zip`

- Try to extract it, OoOoOoPs ! .. it requires a password

- We used `fcrackzip` and wordlist `rockyou` to get the password

`$ fcrackzip -v -D -u -p ~/Wordlists/rockyou.txt Boss_Message.zip`

- You will find a file `2^2` contains an encrypted text seems like a flag and an image with name `This_May_Help.jpg`

- It's a `Vignere cipher`, The image helps you with the key `MORGAN`

- Decrypt it and get your flag ;)

We used [Dcode](https://www.dcode.fr/vigenere-cipher) \:D/
