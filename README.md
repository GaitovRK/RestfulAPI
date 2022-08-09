# RestfulAPI
### The Anatomy Of A Request #
It’s important to know that a request is made up of four things:
#### The endpoint
The endpoint is the HTTP address consisting of root endpoint and the path
#### https://www.smashingmagazine.com/ is the root-endpoint and /tag/javascript is the path.
#### /users/:username/repos
Any colons (:) on a path denotes a variable. You should replace these values with actual values of when you send your request. In this case, you should replace :username with the actual username of the user you’re searching for. If I’m searching for my Github account, I’ll replace :username with zellwk.
The final part of an endpoint is query parameters. 
When you try to get a list of a user’s repositories on Github, you add three possible parameters to your request to modify the results given to you:

 
 
#### The method
#### The headers
#### The data (or body)
