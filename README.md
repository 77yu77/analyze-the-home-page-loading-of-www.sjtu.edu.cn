# Analyze-the-home-page-loading-of-www.sjtu.edu.cn
## Searching for the IP address

   After inputting "www.sjtu.edu.cn", the browser will search for the IP address correspnding with
 it, known as DNS resolution.  
   1. First, it will search from the browser cache.
   2. If the website is not in the browser cache, the browser will scour the domain name and IP address
      Hosts.
   3. While searching for nothing, it will find the IP address in the Router cache.
   4. While searching for nothing, the browser will come to the DNS cache to find the IP address.
   5. If the following steps couldn't solve the problem, the DNS will search the IP address through the 
      "root" DNS servers.
      
## Other management to display the page
   After searching for the IP address, the server uses a pattern known as MVC to manage the view.
   And then the server sends the data to the browser. And the browser will make the page on the basis of 
   the data.
   
   
