# Lab Report 2
## Server code 
![Image](F.png)
![Image](G.png)

## First Screenshot
![Image](A.png)
> For this first screenshot the method that is called is the `handle` method which is derived from the `MessageHandler` class. The argument that is passed through the handle method is the `HttpExchange t` argument which has the details of the request and the relevant field before the request is made is the `chatHistory` field which is initially empty. The field `chatHistory` has its values changed by this specific request as it was initially empty and after this request it will contain the message "jpolitz: Hello\n".

## Second Screenshot
![Image](B.png)
> For the second screenshot the same method as the one utilized above is called again which is the `handle` method that is again derived from the `MessageHandler` class. The argument that is passed this time is the `HttpExchange t` argument which now contains the new request made at the end of the server's url. The relevant field before this request is made is the `chatHistory` field which before the request is made contains the "jpolitz: Hello\n" string in it. After the request is made the relevant field will now contain the aforementioned string as well as "yash: How are you\n".

## Absolute path to Private Key
![Image](C.png)

## Absolute path to Public Key
![Image](D.png)

## Terminal Interaction
![Image](E.png)

## New Information
> From the last two weeks I have learned how to both initialize a server and somewhat create one myself based on the template that was provided to me. I also learned more about the interaction between the host of the server and the server itself on a very fundamental and basic level which has helped me better understand how servers work as a whole. I also learned how to generate keys.
