# Myshop_api
Project my shop api

# Installation of modules

In js file open terminal.

# Installation node.js

npm init
npm install express --save

# Installation vue.js

Download Development Version
Write "<script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"></script>" in index.html

# Creation of Shop site in HTML 

Create a file named index.html
Use html:5 to start 

# Head

Insert a logo
Create a navbar with login, home, shop and magazine
Add a link to these words
Insert a cart image with a link
Create a searchbar with js
Create a filter with 3 options: Best match, Ascending price, Descending price 

# Body

Create 3 filters: Category, Color and Collection with many options
Use js to create a slidebar and a slide container
Create containers 3 on the first line and 4 below
In these containers insert pictures of products, prices of products, names of products and categories of products
Under every container insert a grade picture

# Footer

Create a pagination: create containers with links on each texts
Add a background
Modify style of pagination with the balise <style>

# Creation of CSS 

For each text use "font-family: 'Courier New', Courier, monospace;"
Make the layout with some styles: bold, italic, font-size
Use text-align and margin to place elements on the shop page
Modify the color of the elements with the balise <color> and the color of your choice
Use percentage to make responsive the shop

# Manage interface permissions

- Administration interface : 3 Menus --> "PRODUCTS" , "CATEGORIES" et "USERS

    * PRODUCTS brings us back to a table that will contain: - Product
                                                            - ID
                                                            - Category
                                                            - Actions (Edit/Delete)

    * CATEGORIES brings us back to a table that will contain:- ID
                                                             - Name
                                                             - Actions (Edit/Delete)

    * USERS brings us back to a table that will contain:- ID
                                                        - email
                                                        - Roles
                                                        - Password
                                                        -Full Name    

 
This interface will allow you to manage the user's permissions. Each user (Administrator / client) connecting
to the MyShop site will obviously not have the same permissions. The administrator will be able to create, modify or delete items
present in the table unlike a client who will not have all these permissions.
