# Ecommerce

Build a fullstack E-commerce website with the help of Springboot as backend, Angular as client side code and MySOL as a database.

<b>Backend code</b> :- <b>https://github.com/neekhara22/Ecommerce/tree/master</b>

<b>Frontend code</b> :- <b>https://github.com/neekhara22/Ecommerce/tree/frontend</b>

: : In my first commit I am fetching a list of products with its price and units which are available in stock. The changes looks like after commit is:-

![image](https://user-images.githubusercontent.com/100702414/221408292-02a7a01d-46f7-4c83-ad73-b07a6b780f9e.png)

: : In Second commit I added bootstrap and fortAwesome dependency for styling and added html template. In this I added some products and script by running a script in the MySQL workbench. The changes looks like after commit is:-

![image](https://user-images.githubusercontent.com/100702414/221429818-a7b394a8-a346-4d44-ae68-408668e34c70.png)



: : In third commit I define routes, configure router and define router outlet. Setup router links to pass category id param, enhance ProductListComponent to read category id. Modify backend REST repository according to search product based on their category and lastly update Angular service to call new URL on Spring Boot app. The changes looks like after commit is:-

![image](https://user-images.githubusercontent.com/100702414/221435113-1b24f2bc-5334-4c1b-bfba-d705f2c711b6.png)

: : In my new commit I have change the Spring Boot app to expose the entity ids, Create a class ProductCategory and new component in angular. Enhance component to read data from product service. In HTML remove hardcoded links with menu component. The changes looks like after commit is:-

![image](https://user-images.githubusercontent.com/100702414/221657583-c2f1bf89-aa87-4041-bc13-a80e538ca7ef.png)

: : In my new commit I added the functionality from which I can search the product via text from search button for this I have added the new search method in the spring boot app. I created new component for search, added new angular route for searching, update the SearchComponent to send data to that search route and enhance ProductListComponent to search for products with ProductService in angular. The changes looks like after commit is:-
<br>
<b>If product matches by search value</b>
![image](https://user-images.githubusercontent.com/100702414/221684469-03d2f7cc-76bf-4656-869d-ed61204abe01.png)

<b>If no product is listed as per search</b>
![image](https://user-images.githubusercontent.com/100702414/221685081-e5ee16ef-0fbf-429c-996b-f19e5256aa23.png)

: : In this commit I added functionality to fetch the individual master detail of a product by its Id on Angular, for this I created a new component for product details and add new router for it, add that router links to product-grid-list HTML page. Enhance ProductDetailComponent to retrieve product from ProductService, update ProductService to call the URL on Spring Boot and update HTML page for ProductDetailsComponent to display product details. The changes looks like after commit is:-

![image](https://user-images.githubusercontent.com/100702414/221973150-f5996f49-6bb7-48fe-a901-ccfa5c0b74de.png)

