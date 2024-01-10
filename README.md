# basic-cors-anywhere-example
Good for localhost environments!  
usage: fetch("http://localhost:8080/https://example.com");


Taken created from the basic example found in the readme:  
https://github.com/Rob--W/cors-anywhere  

I put as example as my own repo for future referance and usage.

# Setup
1) clone the repo
2) npm install;
3) node server.js
4) open any tab in the browser and navigate to any site.
5) from the developer tools console run:  
      i) fetch("http://localhost:8080/https://example.com")  
      ii) fetch("https://example.com")  
6) take not of the network tab and that the first request passed and the second request resulted in a cors error!
