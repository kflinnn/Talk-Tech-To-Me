# Talk-Tech-To-Me

## Purpose

A CMS-style blogo site similar to Wordpress site, where developers can publish their blog posts and comment on other developers' posts as well.

When given a CMS-style blog site, the user visits the site for the first time and is presented with the homepage, which includes existing blog posts if any have been posted. When they click on the homepage option, they are taken to the homepage, when they click on any other links in the navigation, they are prompted to either log in or sign up. If they choose to sign up, they are prompted to create a username and password, save them and they are logged into the site. When revisiting the site later, they are able to log in and are prompted to enter in their credentials, thus signing them in. When they are signed in to the site, they see navigation links for the homepage, the dashboard, and the option to log out. They are then able to navigate to the different pages, view blog posts, create their own blog posts, and comment on existing posts as well. They're also able to update or delete any posts or comments that they have created. This was achieved by using node.js, Sequelize, and other npm packages. 

## Examples

Comment, Post, and User Controllers:

![Screen Shot 2023-04-25 at 2 35 40 PM](https://user-images.githubusercontent.com/116764540/234370815-49b3e935-3531-4633-bd96-390bd8bf722a.png)

![Screen Shot 2023-04-25 at 2 35 50 PM](https://user-images.githubusercontent.com/116764540/234370826-9c66bc10-2bf1-4818-bc83-b7acb1117454.png)

![Screen Shot 2023-04-25 at 2 35 57 PM](https://user-images.githubusercontent.com/116764540/234370840-95ae51a1-8864-42cf-84d2-6bcd1d39359a.png)


User Model:

![Screen Shot 2023-04-25 at 2 36 25 PM](https://user-images.githubusercontent.com/116764540/234370960-3c0a3686-6467-42e1-9e4c-f4e3df3ae3a4.png)


Main handlebars:

![Screen Shot 2023-04-25 at 2 36 41 PM](https://user-images.githubusercontent.com/116764540/234371069-af3b082f-5e59-419c-9a6d-732ce9c1430e.png)


## License

MIT License

Copyright (c) 2023 Kelley Flinn

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

##Sources

UCF Bootcamp Spot

## Technologies Used

Language: JavaScript

NPM: Node.js

NPM: bcrypt

NPM: Sequelize

NPM: express.js

NPM: dotenv

NPM: express-handlebars

NPM: mysql2

## Deployment Link

https://young-tundra-85939.herokuapp.com/
