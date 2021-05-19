1. Create Heroku account: https://signup.heroku.com/
2. Install Heroku CLI: https://devcenter.heroku.com/articles/heroku-cli#download-and-install
3. Go to your project folder and create ```index.php``` file with a content: ```<?php header( 'Location: /index.html' ) ;  ?>``` (make sure your project have ```index.html``` and you also can replace ```index.html``` by another file you want to run).
4. Tạo Heroku App trên terminal:
```
cd your-project-path
git init
git add .
git commit -m "My site ready for deployment."
heroku login // bypass if you already login on Terminal
heroku apps:create my-static-site-example // Thay my-static-site-example bằng 1 tên khác, cẩn thận bị trùng
git push heroku master
heroku open
```
5. Next time deploy, just: 
```
cd your-project-path
git add .
git commit -m "your message"
git push heroku master
heroku open
```
