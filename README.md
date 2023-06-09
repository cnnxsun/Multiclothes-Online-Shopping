# Multiclothes-Online-Shopping


This project is the frontend and backend development of the fashion online shopping business domain that was developed by Russarin Eaimrittikrai, Chaninan Phetpangun, Penpitchapa Pantaraksakul, and Warangkhana Srichan. The technologies that were utilized in this project are HTML, CSS, JavaScript, Node.js, Express, and SQL.


* How to Install and Run the Project


1. Download and unzip the zip file name sec2_gr12_pj2_ID6488021_6488061_6488175_6188096.zip
2. There will be 1 pdf file, 1 SQL file, and 2 folders in the zip file.
* sec2_gr12_report.pdf: Report of the project 
* sec2_gr12_database.sql: Database of the project
* sec2_gr12_ws_src: Source codes of the web services
* sec2_gr12_src: Source code and readme file
3. Open MySQL to run the sec2_gr12_database.sql
4. In MySQL create a username and password by clicking 
* Server -> User and Privileges
* Create new account 
Username: multiclothes
Password: 1234
* Set Schema Privileges of multiclothes database to allow: SELECT, INSERT, DELETE, UPDATE
* Then Apply
5. In the sec2_gr12_ws_src folder, you will find the files and input them into Visual Studio Code.
* package.json
* package-lock.json
* ws_backend.js
6. In the sec2_gr12_src folder, you will find these files and input them into Visual Studio Code.
   * package.json
   * package-lock.json
   * Html folder:
HTML
* HomePage.html
* Admin.html
* Search.html
* DetailPage.html
* DetailPageOne.html
* DetailPageTwo.html
* DetailPageThree.html
* DetailPageFour.html
* DetailPageFive.html
* DetailPageSix.html
* ProductManage.html
* ProductManage1.html
* ProductUpdate.html
* WelcomePageAdmin.html
* User_Account_Management.html
* About_us.html
CSS
* HomePage.css
* Admin.css
* DetailPageAll.css
* DetailPageEach.css
* Nav.css
* ProductManage.css
* ProductManage1.css
* SearchPage.css
* User_Account_Management.css
* WelcomePageAdmin.css
                JS (For Web services interaction)
* client.js
* client2.js
* client3.js
* clientPd.js
* clientPd2.js
PNG
* MultiClothesLogo.png




7. To view website pages, you must open 2 terminals, split them, and run ‘npm start’ in each terminal for
   1. ws_backend.js by typing cd sec2_gr12_ws_src, then npm install
   2. ws_ui.js by typing cd sec2_gr12_src, then npm install


8. After running the codes in the VSCode, Input the URL ‘http://localhost:3031/’ in the web browser of your choice (recommended: Google Chrome)


* How to Use the Project


1. The first page to access is the Home Page which contains a navigation bar that links to other pages, articles, and a footer.
2. The first element in the navigation bar is the Home Page which links to the Homepage of the website. (http://localhost:3031/)
![Screenshot 2023-05-24 124606](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/1adb3959-6c55-42b7-bab5-9e321a4d3f30)
![image](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/86a29ccf-54ee-42f5-a4f0-04870b579a0c)

3. The second element in the navigation bar is Search which links to the Search Page. (http://localhost:3031/search)
* Search Page includes 3 criteria which are product name, id, and brand.
* Once you click on the magnifying glass button on the Search Page to search, you’ll see the product information from the database, based on your search input.
![Screenshot 2023-05-24 135717](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/3e24b2b6-109d-4ac1-820f-1d551f9c117d)

4. The third element in the navigation bar is About Us which links to the Page that contains information about the developers of the website (http://localhost:3031/about-us) 
![Screenshot 2023-05-24 140026](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/e05a83e5-504a-4fe1-ae59-38e17b0293fc)

5. The fourth element in the navigation bar is Administrator which links to the login page for administrators. (http://localhost:3031/admin-login)
* You must enter the valid username and password that exist in the database in order to access the administrator’s pages.
* Once you successfully log in, you’ll access the Homepage for administrators.
* On the Homepage for administrators (http://localhost:3031/adminhome), there are two buttons: User Account Management and Product Management.
![Screenshot 2023-05-24 140944](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/f050c109-1a4d-4214-9851-31010cc22b32)
![Screenshot 2023-05-24 141112](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/58db3c45-72c3-48d9-a6c1-bf7402a1905d)

6. The User Account Management page (http://localhost:3031/admin-manage)
* It has a form for adding a new administrator 
* You can view or search for administrators’ information by using 3 criteria: Admin Num, First Name, and Last Name.
* After searching for administrators’ information, you can delete the administrator's account by clicking the trash can button or edit the administrator’s account information by clicking the Edit button.
![Screenshot 2023-05-24 141314](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/33c8e5ca-b60e-48a7-bb35-1991de04b507)

7. The Product Management page will show the list of own products (http://localhost:3031/product-lists)
* You can delete and edit the products 
* You can add a new product by clicking on the ADD NEW button which links to the form to fill in the new product information. (http://localhost:3031/product-add)
![Screenshot 2023-05-24 141502](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/bcd12855-deb3-4135-8985-93b3a90480d8)
![Screenshot 2023-05-24 141553](https://github.com/cnnxsun/Multiclothes-Online-Shopping/assets/125891778/926c1e9d-7bf3-4ea8-b700-92bd87e972da)


* Remarks 

1. The elements in the footer of every page aren’t linked to anything.
2. Homepage:
* The Shop Now button doesn’t link to any page.
3. Search Results Page: 
* The sort By drop-down button isn’t able to perform any action.
* Heart icons on every product card aren't able to perform any action.
4. Product Detail Pages:
* Add to Cart button isn’t able to perform any action.
* The heart button isn’t able to perform any action.
5. About Us Page:
* Social media icons on every member card aren’t linked to anything.
* Contact email buttons on every member card aren’t real emails.
* References or resources


1. Home Page
* Background image of Homepage
https://unsplash.com/photos/TS--uNw-JqE 
* Zara logo
https://logos-world.net/zara-logo/ 
* H&M logo
https://1000logos.net/hm-logo/ 
* Fila logo
https://logos-world.net/wp-content/uploads/2020/10/Fila-Logo.jpg 
* Adidas logo
https://www.zenbusiness.com/blog/adidas-logo/ 
* Pull and Bear logo
https://1000logos.net/pull-bear-logo/ 
* Zara New in 1
https://www.zara.com/uk/en/rustic-ribbed-t-shirt-p02298008.html?v1=252802412&v2=2184058 
* Pull&Bear
https://www.pullandbear.com/us/worker-jacket-with-corduroy-collar-l04710527?cS=707&pelement=567077050 
* H&M
https://www2.hm.com/en_us/productpage.1155288001.html 
* Instagram Icon
https://www.flaticon.com/free-icon/instagram-logo_87390 
* Facebook Icon
https://www.flaticon.com/free-icon/facebook_1077041 
* Twitter Icon
https://www.flaticon.com/free-icon/twitter-logo-on-black-background_60580 
* TikTok Icon
https://www.flaticon.com/free-icon/tiktok_3938055?related_id=3938074&origin=search 




2. Search Results Page and Product Detail Pages
* Product pictures and information 1 H&M
https://th.hm.com/th_en/oversized-v-neck-sweatshirt-1127931002008.html 
* Product pictures and information 2 H&M
https://th.hm.com/th_en/canvas-hi-top-trainers-1059782007005.html 
https://th.hm.com/th_en/canvas-hi-top-trainers-1059782007005.html 
* Product pictures and information 3 Zara
https://www.zara.com/uk/en/fitted-double-breasted-blazer-p02297707.html?v1=250900056&v2=2228619 
* Product pictures and information 4 Zara
https://www.zara.com/uk/en/heart-print-t-shirt-p00495428.html?v1=229007752&v2=2230614 
* Product pictures and information 5 Fila
https://www.fila.com/mens-mb/1BM01866.html?dwvar_1BM01866_color=107&fromList=Category%3A%20Shoes&gridposition=7&cgid=shoes 
* Product pictures and information 6 Fila
https://www.fila.com/brandon-maxwell-cut-out-cami-dress/TW23C966.html?dwvar_TW23C966_color=648&fromList=Category%3A%20Collaborations&gridposition=2&cgid=collaborations 


3. Product Management Page
* Product1 image 
https://www2.hm.com/ja_jp/productpage.1036121011.html 
* Product2 image
https://th.hm.com/th_th/puff-sleeved-crop-top-1138624001009.html 
* Product3 image
https://www.supersports.co.th/th/crocs-crocs-classic-mega-crush-clog-unisex-casual-shoes-cr024sh127dath?MTg0LGNkcw%3D%3D=134287&NDEwLGNkcw%3D%3D=134097
