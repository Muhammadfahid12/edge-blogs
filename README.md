# EDGE BLOGS
#### Video Demo:  https://youtu.be/4-5dJe-dwlY?si=Xnfo4QnUY09tz2QD
#### Description:
My cs50 final project is about a Blogging website called EDGE BLOGS.
A user will required to register and then he can read blogs availble on this webiste.
A user can also write his own blog and post it.
A user can view blogs written by him and also delete his blogs.
Edge Blogs will keep record of each blog author and also timestamp when it is written.
A user can logout easily by just clicking on Logout option

## Validation Checks I have used:
User can register once over a username.
user can't post any blog without title or content.
user can't delete other author blogs.
Two blogs can not have same title.
user can't read,write blog without login.

## Technlogies Used in Project:
Used HTML for structure
Used CSS for styling
Used JINJA template
Used Flask for Back-end operations
Used SqLite3 for storing data

### Files Structures
## static
This folder contains one images folder which contains images used in project, a stytles.css and write.css file

## templates
this folder contains all the required HTML content with multiple files.
aplogy.html used for rendering to apology statement.
blog.html is used to represent blogs sections
blogread.html used for displaying blog completely
home.html represents main home page
jinjga.html is used to support jinja tempalate in other html files
jinjaforwrite.html is used for writing blog page.
layout.html defines main layout of webpage
login.html is used for login page
register.html is used for registraion of users
write.html is used to page used for writing blog



## helpers.py
helpers.py contains two functions first is apology function which return a picture and an error code like 404 or it can be
any error code . it will execute when something that went wrong.
second function is login_required(f) which is used to ensure that before certain action,user should be login;

## app.py
This is our main file which contains many functions.Let's have a tour of this
It is connected to database named as bloddb

 register for registering users.When user will click on register it will render to /register where user write username,password and a confirm password. Password is stored by using a hash_function it database.

 login for logging functionality. User required to enter his username and password.
 logout for logging out.
 blog which shows blogs writtem by all users till date

 write for writing blog. A user has to write Title and content.These fields should not be empty.After,User can click on post button to post blog and it can be seen in /blog.

 read_blog is used that when user click on read more button,a new page will render and whole blog can be reas easily.
 delete for deleting the blog by user itslef
 profile for displaying blogs written by user.It would not represents all blog posted on the website but blogs only written by user.

## Setup and Running of code
Require Flask to run this code on your codespace
To run this website use simply "run flask" command.


## Contributing 💡
If you can help us with these. Please don't hesitate to open a [pull request](https://github.com/MugheesMb/developerIdentity/pulls).

For any query reach me : https://github.com/Muhammadfahid12
Thank you!






