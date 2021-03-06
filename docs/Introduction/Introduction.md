
# Introduction

Comet technology — allows sending arbitrary messages to client through server initiative — it’s a push notifications. You can use push technology to delivering messages. For the correct work of push notification always use a push service. You can perform these tasks because of permanent connection between browser and Comet server.  Here used websocket technology. For those browsers whose don’t support websocket technology always used long polling AJAX query mechanism.

# How push notification works

On this scheme you can see field of using Comet server in working process. We can notice next way (side) of notification: 

  - Browser opens page of your site.
  - After loading this page, JavaScript establishes permanent connection with Comet server.
  - While page is open, your server can send random message to client. It appeals via PHP API to server and transfer message for browser.
  - Comet server users open connection with browser. Than server delivers message to browser.
  - JavaScript API delivers this message to your callback.

![](https://comet-server.com/wiki/lib/exe/fetch.php/:scheme-of-comet-using.gif )
# Advantages of using push service

Comet server permanently maintain opened connections and this let to unlade (unload) structure of your site. Comet server realized on C++ for maintain a big amount of opened connections with browsers and server always correct solve (perform) the current tasks.

# Why PHP is not available in this case?

Push notifications can be implemented by PHP, but PHP need to use more memory consumption and time rate, so server will be overloaded. Therefore, we recommend using specified tools.

# Practical use of push notifications

  * Online chats;
  * Notifications about some events;
  * Browser-based multiplayer game;
  * Online-updating graphics;
  * Joint editing documents;
  * Opportunities list of Comet server;
  * Sending messages from server to specific user (by id);
  * Sending messages from server to all subscribers;
  * Determination all of online users (who are active at this moment);
  * Getting statistics by real-time about summary amount of online users.

 
# Links
We recommend you to read these articles:

  * [PHP chat example](/docs/Examples/PHP%20chat%20example)  
  * [JavaScript API](/docs/API/JavaScript%20API/JavaScript%20API)
  * [CometQL API](/docs/API/CometQL/CometQL%20API) 
  * [CppComet](https://github.com/CppComet/comet-server) 
  * [An example of sending a message from a bash script](/docs/Examples/An%20example%20of%20sending%20a%20message%20from%20a%20bash%20script)