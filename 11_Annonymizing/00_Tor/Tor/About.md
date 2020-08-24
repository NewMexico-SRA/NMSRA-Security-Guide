# Tor
The Onion Router (Tor) connects users to the internet annonymously when properly utilized. It does so by 'Onion Routing', a process of multi-level encrytion and passing data through Tor nodes.  
Imagine a magic envelope that only opens for the intended recipient. That recipient is the 'entry node'. The entry node knows who sent the request, but not the final destination. It removes the first envelope and all the information of where it was from. Inside is a second magic envelope intended for the 'relay node', which only knows the enrty and exit node. It gets rid of the envelope, revealing the third and final envelope. This final envelope is for the 'exit node'. The exit node can look into the envelope at the now unencrypeted internet data and send it to the server that the Tor user is connecting to. Although the exit node knows the contents and destination it doesn't know the origin of the request. The nodes continue to work together to transport the content back to the annonymous Tor user.  
These envelops are encryption layers. Onions have layers, hence the name: The Onion Router.