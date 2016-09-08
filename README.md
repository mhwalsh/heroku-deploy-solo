##Practice Heroku Deploy

#### Create an account on Heroku
[https://signup.heroku.com/dc]()

#### Follow the setup guide for Node.js appilcations
[https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction]()

On the "Prepare the App" section, instead of cloning heroku's example node application, **use your own node express application** like the one we have been working on in class.

**Remember:** make sure you use ```listen(process.env.PORT || 3000);``` in order to support heroku’s automatic port assignment.

**Remember:** to include an npm start script.

Once complete, push the assignment to both GitHub and Heroku and submit both URLs in the assignment app.