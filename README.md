## Blog
# Author
    Aaron Ekal
## Email
    ekalaaronkalale@gmail.com
## Project description
    This is a flask application that allows writers to post blogs, edit and delete blogs. It also allows users who have signed up to comment on the blogs that has been posted by a writer. 

## Live link
    
## User story
    * A user can view the most recent posts.
    * Register to be allowed to log in to the application
    * A user sees random quotes on the site
    * A writer can create a blog from the application and update or delete blogs I have created.

## Development
    * Fork the repo
    * Clone the repo in your machine but ensure you have all the necessary modules.(You can find them in the set up instructions above) git clone https://github.com/Aaron-Ekal/Blog
    * Create a new branch git branch contributions
    * Edit your changes in your branch
    * Run the application python3.8 run.py
    * Push your changes so we can have a view!
## BDD
|Behaviour|Input|Output|
|---------|-----|------|
|Load page|On page load|Get all blogs,select between Register and login|
|select signup|email,username,password|redirect to login|
|select login|username and password|redirect to page with blogs that have been posted by writers and be able to subscribe to the blog|
|select nerw post|comment|form that you input your comment|
|click on submit||redirect to all comments template with your comment and other comments|

## Technologies used
    * Python3.8
    * Flask
    * Heroku
 ## Known bugs
    updating blog gives an internal server error

## License
    * MIT License
    * Copyright (c) 2022 aaron Ekal