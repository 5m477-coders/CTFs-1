#### Just Smile

The challenge was a given image of smile emoji named `smile.png`

- Use `exiftool` to check image details

You will find a comment says `This_Is_Not_the_Flag_but_Useful` .. it will be useful soon ;)

- Try to get the hidden files from the image using `binwalk`

`$ binwalk -e smile.png`

It says that there's a ***ELF*** file in the image (lucky \:D/ )

```
  ELF file is an executable file on Linux \:D/
```

- Go to the file .. change its permission to give it an execute permission

`$ chmod 777 1378D.elf`

- Run the file `$ ./1378D.elf` .. it will ask you for a password

- Use the useful comment :D .. and here we go the flag is here ;) 
