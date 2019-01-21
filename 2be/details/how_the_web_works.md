## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?
    1. The browser and operating system will determine if they know they the IP address already (configured on computer or in cache).
    2. The operating system then asks the resolving name server for any IP addresses it doesn't know. If it doesn't know where the IP address is, it will pass the query along to the Root name servers.
    3. The resolving name server will put the root information into it's cache and pass the query along to the Top Level Domain (TLD) servers. In this example it would be the com name servers.
    4. The resolving name server will put the TLD information into its cache and then be passed along to the correct Authoritative Name Server (ANS) with help from the Domain Registrar.
    5. The resolving name server then takes the IP address it gets from the ANS, puts it in cache and gives the reply back to the operating system.
    6. The operating system then gives it to the browser which makes the request to the correct IP address. 
 
1.  What does HTTP stand for?
 * Hyper Text Transfer Protocol
 
1. 	What protocol does the World Wide Web use?
  * HTTP
 
1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?
  * Internet Protocol
 
1. 	What does DNS stand for? 
  * A. Domain Name System
  
1. 	How are text domain names matched to their respective numeric IP addresses.
  * Domain Name Servers

1. 	What is the client?
  * E. The computer which the IP address belongs to
  
1. 	What does URL stand for?
 * Uniform Resource Locator
 
1. 	What are protocols
 * D.	The standardised method for transferring data or documents over a network
 
1. What does DNS stand for?
 * Domain Name System
 
1. what is the `www` portion of a url?
 * World Wide Web
 
1. What is The markup language used for all web documents?
 * HTML - Hyper Text Markup Language
 
1. What is the organization that monitors web technologies?
 * World Wide Web Consortium
 
1. What is the Protocol for transferring web documents on the Internet?
 * HTTP - Hyper Text Transfer Protocol
 
1. What matches the domain names with numeric IP addresses?
 * Domain Name System (DNS)




