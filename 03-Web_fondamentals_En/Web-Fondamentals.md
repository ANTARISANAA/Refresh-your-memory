## Web Fondamentals
         Web is computer network consisting of a collection of internet sites that offer text and graphics and sound and 
        animation resources through the hypertext transfer protocol.
        
 ### **So how the Web work ?**
         When a user is searching for a website , he enter a URL in his browser, the browser send a request to DNS server, who
         translate domane name to an IP adresse, that going to be search in the server who will send the response to the user by
         showing the website interface .
        
 ### **Client-server model :**
 + **Client :** Computer who ask data (machine or program).
 + **Server :** Computer who give data (computer or machine). He is always listning for a request and it used to serve clients, we have two types:
      + Web server.
      + Data base server.
      
 + This model is based on :
      + **Centralized structure.**
      + There's another **Decentralized structure.**
      + **Peer to Peer:** Where the client and the server are located in the same machine (all the computers are fontctionally equal). 
 ### **HTTP://**
 **HTTP** (Hypertext Transfer Protocol): a protocol for transferring hypertext documentsis, it's a way of formatting and transmitting messages on the internet.
 ### **HTTPS://**
 **HTTPS**  (Hypertext Transfer Secure Protocol): in this protocol the data sent is encripted by **SSL**(Secure Socket Layer) or TLS (Transport Secure Layer ).
 
 ### **Methods**
 + **Get :** we use it when we wont to fitch data from the server.
 + **Past :** We use it when we're posting data.
 + **Put :** Update data that we have already on the server.
 + **Delete :** Delete data from the server.
 ### **Request content **
 + Header :
      + General header :
          + Method (get or post ).
          + Status code .
          + Path .
          + Remote adress.
          + Protocol.
      + Respose header :
          + Content type.
          + Content length.
          + Server.
          + Date.
          + Set-Cookie.
      + Request header :
          + Cookie.
          + Accept-XXX.
          + Authorization.
          + User refere.
          
 ### **Http status Codes :**
  + **200** : Ok.
  + **201** : Ok created.
  + **301** : Moved to new URL.
  + **304** : Not modifited.
  + **400** : Bad request.
  + **401** : Unauthorized.
  + **404** : Not found.
  + **500** : Internet server error.
