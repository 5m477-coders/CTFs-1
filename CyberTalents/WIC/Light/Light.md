#### Light

The challenge was a given image named Light

- Use `$ exiftool Light` to check the image .. it's normal :-?

- Use `$ binwalk -e Light` to extract the hidden files

You will find *5B.zlib* file

- Try to `$ cat 5B.zlib`, You will find Zeros & Ones at the end of the file .. (interesting ;) )

- Convert the Zeros & Ones and get your flag \:D/

We used [Binary to Text converter](https://www.rapidtables.com/convert/number/binary-to-ascii.html)
