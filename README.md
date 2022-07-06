## Botanic Merket - T2A2
-------------------
#### by Chen Zhang 
-------------------
### R9	A link (URL) to your deployed app:
Heroku: https://botanicmarket.herokuapp.com/
<br>
### R10	A link to your GitHub repository:
GitHub: https://github.com/OrangeKami/Chen_Zhang_T2A2
<br>
## R7 R8 Problem overview:
The problem I am trying to solve is to create a marketplace platform to buy and sell  plants and assossicatd product.

This is the problem that beacuse of the Covid padanmic, more and more extreme weathers and also the inflation, makes 
online shopping is priority choice for people's buying instead of traditional local market(Sunday Market, Bunnings and etc.)

Evaryone loves greens at home, especially when you have to spend most of daytime at home or in office. A little green plant is the key to help you relief and relax. This marketplace app I have build, allow user to buy and sell their own plants product and insite message to sellers just like local store. 



## R11	Description of your marketplace app:

### Purpose:
This two-sided marketplace web application allows signed in users to post up plants items that they would like to sell, and also be able to purchase listings from other user. A registered and signed in user should be able to quickly create a listing without great difficulty, that should include basic details of the listing item, and also upload an image. Insite message system to help users communicate easier and detail.
### Functionality and features:
|Functionality | Description|
|---|---|
| Accounts | Users are able to create new accounts when signing up, and must be logged in to create new listings of listing items, or purchase listings. All users can view items without having to sign up or log in, however if they click on an item, they will need to sign in to view the individual listing and see the options to message the seller or add the listing to watchlist. A user can change/update their profile at any time and has its own avatar.
| listings | Once a user has logged in, they are able to create a new  listing by inserting the required information about the listing, and uploading an image is optional. If they do not upload an image, a default image will be added on.  Listings can be updated or edited but only by the person that created the listing and that person must be logged in to see the edit or delete options of the listing. Once a user has logged out, they will still see all listings. |
| Messages | Buyers and sellers can message each other regarding a listing, and their messages are shown along with the time and name of the person sending the message.  |
| Watchlist or shopping cart | A user who has logged in can place an item in their whatchlist. They can update the list.|
| Search | Anyone can search for an item without having to log in first. The search bar is shown on every page of the app, and allows users to enter keywords which will search through the title and description of listings. |
| Admin| Admin account can access listing items to edit and delet them. And also can see all the users in the market and choose to delete them or not. |


### Sitemap:
![image of sitemap of marketplace app](src/Sitemap%20planning.png)
For different Users
![admin](src/Wireframes/Mapping_%20Admin.png)
![user](src/Wireframes/Mapping_%20User.png)
![guest](src/Wireframes/Mapping_%20Guest.png)

### Screenshot:
index page
![index](src/screenshot/localhost_3000_.png)

listing page
![listings](src/screenshot/localhost_3000_listings.png)

listing detail page
![detail](src/screenshot/localhost_3000_listings_60.png)

message page
![message](src/screenshot/localhost_3000_conversations_1_messages.png)

singin/signup page
![singin](src/screenshot/botanicmarket.herokuapp.com_d_users_sign_in.png)
![signup](src/screenshot/botanicmarket.herokuapp.com_d_users_sign_up.png)

admin page
![admin](src/screenshot/botanicmarket.herokuapp.com_listings.png)
### Target audience:
The target audience are for anyone with a working smartphone, tablet, desktop devices with connection to the internet. Users don't need to have a credit card for purchasing, as they may want to contact the seller via e-mail or insite message system tp arrange alternative payments and exchange of the goods. As this app is also targetted towards audience with intention to purchase locally, hopefully travelling shouldn't too much of a hassle. Alternatively, the seller and buyer may arrange for items to be delivered if they are unable to get out. For example, stuck in isolation or bad weather.

### Tech Stack:
* Front end: HTML5, CSS, SCSS, BOOTSTRAP, Javascript
* Back end: Ruby 2.7.5, Ruby on Rails 7.0.3
* Database: PostgreSQL
* Deployment: Heroku
* Project Management: Trello Board
* DevOps: Git, GitHub, VS Code, Webpacker, Bundle, Yarn and Balsamiq
<br>
## R12	User stories for your app:
As a user when you singed in, you can buy and sell plants items on market. we will discuuse this into two parts:

***As a Seller***

* I do not want anyone else to edit or delete my listings.
* I want to log in with my email and password to edit or delete my listings.
* I want to log in first before seeing messages that have been sent to me.
* if I receive a message, I want to also see the time stamp of when the message was sent and who it was from.
* I want to be able to create more than 1 account on the application.
* I want to update my details on my profile.
* I want to delete my account at any time.
* if someone wants to buy my sticker or message me, then they should have a user profile with the app.
* I do not want others to access my account or change my profile information.

***As a Buyer***

* I want to see listings without having to sign up or sign in.
* I want to see an image of the listing, its name, description, category and price.
* I want to send a message to the seller about a particular listing.
* I only want my messages to a seller to be shown to that seller and not be made public.
* I want to be able to add item to a whtchlist/shopping cart.
* I want to be able to delete items from the watchlist.
* I do not want others to access my account or change my profile information.

***As a Admin***
* I want to see a table of all users and can delete them when needed
* I want to see a table of all listings and can edit them and delete them without any permision.

## R13	Wireframes for your app:
placeholder

## R14	An ERD for your app:
placeholder

## R15	Explain the different high-level components (abstractions) in your app:
placeholder

## R16	Detail any third party services that your app will use:
placeholder

## R17	Describe your projects models in terms of the relationships (active record associations) they have with each other:
placeholder

## R18 Discuss the database relations to be implemented in your application:
placeholder

## R19	Provide your database schema design:
placeholder

## R20	Describe the way tasks are allocated and tracked in your project:
placeholder
