#### [WantBiscuits](http://35.197.254.240/wantbiscuits/)

The challenge was Web App just saying `Hello anonymous`

- Check the request headers in `network`

 You will find set-Cookie in Response Headers named `userCookie`

- Take the value to an URL decoder .. the result seems to be encoded with base64

- We used [base64 decoder](https://www.base64decode.org/),

then we got serialized array

``` O:4:"User":2:{s:8:"userName";s:9:"anonymous";s:7:"isAdmin";b:0;} ```

- Edit it to test

``` O:4:"User":2:{s:8:"userName";s:5:"admin";s:7:"isAdmin";b:1;} ```

- Encode the array again with [base64 encoder]()

- We used `EditThisCookie` extension to modify the Cookie

- Refresh the page and Enjoy the flag ;)
