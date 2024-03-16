# Shopping Cart

## Description of the project:
 This is a standalone React application showcasing a shopping cart template for a website. Users can view restocked products using Strapi tools and interact by adding products to the cart, dynamically updating the checkout total. The cart includes the option to remove products. 

## How to Run:
This project was initiated using the standalone React method, which connects with the browser as follows: primarily fork it to your local computer, then:
### Open Git Bash and run the following commands:

#### Navigate to the location of the HTML file you want to open in the browser. Then, type:
      ```
      npm install -global http-server
      ```
#### After installation, type:
      ```
      http-server -c-1
      ```
      
You should see output similar to the following:

      ```
      Starting up http-server, serving ./
      
      http-server version: 14.1.1
      
      http-server settings:
      CORS: disabled
      Cache: 3600 seconds
      Connection Timeout: 120 seconds
      Directory Listings: visible
      AutoIndex: visible
      Serve GZIP Files: false
      Serve Brotli Files: false
      Default File Extension: none
      
      Available on:
        http://192.168.1.181:8080
        http://127.0.0.1:8080
      Hit CTRL-C to stop the server
      
      ```

### Open your web browser and enter `localhost:8080` in the address bar. 
The website should load and display the information. If you make updates in VSCode and they're not reflected after reloading the page, be sure to clear the cache.

*NOTE* Please note that before interacting with the restocking button, you need to create your own database using Strapi and ensure it is running. You can learn more about Strapi [here](https://docs.strapi.io/dev-docs/quick-start#_1-install-strapi-and-create-a-new-project). Keep in mind that there are prerequisites to setting up a Strapi app, which you can find detailed information about in the provided link. Once you have your personal database link, make sure to replace my link with yours in the designated space. 


## Roadmap of future improvements:
Several improvements are needed for this application. Starting with the restocking process, I aim to find a method to add products to the list without repetition, incrementing existing quantities or adding new products if necessary. Additionally, I intend to enhance the aesthetic appeal of the page to make it more attractive to clients/users. Furthermore, I plan to implement functionality where adding a product to the cart decreases its stock count, and once stock runs out, the add button is disabled.

## License information:
MIT license.

## Support
If you have any questions, please don't hesitate to contact me email <juliethpbautista@gmail.com>
 . Also I'm open to your ideas and suggestions, and I'm confident that our combined talents could lead to exciting and innovative results. If you're interested in discussing potential projects or exchanging ideas, please let me know.

Let's start a conversation and see where our collaboration might take us.

