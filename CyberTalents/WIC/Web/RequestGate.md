#### [Request Gate](http://35.197.254.240/request-gate/)

The challenge was Web App giving `HTTP ERROR 405`

- Open the developers tool, check `network` tab

You will see error `This page is only accessible via PUT method`

- I used *Postman* to send the PUT request, it returned `405 Not Allowed`

- So I tried to change the URL by adding index, it returned the same

- Then I tried to add `index.php`, and it reveals the flag ;)
