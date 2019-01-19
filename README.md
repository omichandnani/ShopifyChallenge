# ShopifyChallenge
This project is created for shopify challenge
The Filename is Shopify Challenge which has ec-hd-web project.
There are three files in the project  Product.java , Addproduct.java,Student.hbm.xml
Product.java is the pojo file which contains all the table columns declaration defined in Student.hbm.xml
Addproduct.java has two functions save(),returnproduct().
Save():It is use to store the values in the database and also creates the product table automatically will store 3 values 
1.productname
2.price
3.inventorycount
returnproduct():Will accept one argument that will be product name it will be first checked with the database if the product is present 
than the inventorycount is checked if it is greater than zero the product is return and inventory count is reduced by one .
4.In the main method just uncomment the save() function when you want to store any data .
This supports the hibernate ORM framework for storing and reterival of data from the database
The database used is mysql
