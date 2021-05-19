1. Create Heroku account: https://signup.heroku.com/
2. Install Heroku CLI: https://devcenter.heroku.com/articles/heroku-cli#download-and-install
3. Create react app, on terminal: ```npx create-react-app your-app-name-here```
4. Redirect to your app folder: ```cd yourAppFolderPath```
5. Run follow cmd line to create Heroku App and deploy your project to it:
```
cd your-project-path
git init
git add .
git commit -m "My site ready for deployment."
heroku login // bypass if you already login on Terminal
heroku apps:create your-static-site-example // Thay my-static-site-example bằng 1 tên khác, cẩn thận bị trùng
git push heroku master
heroku open
```
