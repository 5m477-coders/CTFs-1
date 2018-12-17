#### GotControl

The challenge was Web App saying

``` Sorry, your IP is not allowed, this server is only accessible from local machine or local LAN. ```


- That means that we should make the request from the local IP in the server network

So, I used `curl` to send the request with Forwarded header

`$ curl --header "X-Forwarded-For: localhost" http://challengeLink`

- The flag is ready to be revealed ;)
