REQUIREMENTS<br/>
XAMPP--> 7.4.1<br/>
Composer-->1.9.1<br/>
Node.js --> 12.14.1<br/>
VS CODE<br/>
GIT<br/>

Upload the required dependencies inorder- to prevent errors and download the specified versions as later versions has compatibility issues.<br/>

Setting up the App<br/>
-download the zip file and extract it<br/>
-place the extracted folder in c/xampp/htdocs<br/>
-open the folder and gitbash here.<br/>
-type:[code .] (Open VS CODE)<br/>
-copy the Databse name from .env folder<br/>
-open xampp controller and run but mysql and apache server.<br/>
-go to browser to open localhost/phpmyadmin<br/>
-click on new at left button on the left side<br/>
-paste the database name and select utf8_general_ci and click create<br/>
-go back to gitbash and type (php artisan migrate)<br/>
-go to database/seeds/DatabaseSeeder.php to check default username password.<br/>
-[in gitbash] type php artisan db:seed<br/>
-Run [php artisan serve] and paste the localhost:8000 address to run.<br/>
-type the set user_id and password and look around.<br/>

