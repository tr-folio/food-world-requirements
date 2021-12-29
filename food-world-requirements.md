# Full-Stack Web Application based on Food Delivery

A full-stack web application has to be built on food delivery system. It will have the following requirement tasks:

## Requirements

### Front-End Part
* Home page with a header, top-banner, discounted foods, all services at a glance, about us, contact us and footer.
* Header will contain a navigational menu containing Home, Order-Now, Career, Login and Events menus. Order-Now will be a dropdown menu having "Order Food" and "Ceremony Arrangement" option. Career menu will be a dropdown menu having "Chef Training" and "Chef Recruitment" options. Login menu will be a dropdown menu having "Login" and "Register" options which will be replaced by user profile picture or user name after login.
* "Order Food" page will show the food items from API call. Each food item will have an image, food name, rating, price and order now button. If discount is applied on a food item, discounted price will have to be shown. After clicking on order now button, a logged in user will be redirected to a private route called purchase otherwise he/she will be redirected to login page.
* "Ceremony Arrangement" page will have a form to fill-up place order for arraning a ceremony, festival, picnic, party etc. It will be a private route.
* "Chef Training" will have a form to fill up to apply for chef training course. It will be a private route.
* "Chef Recruitment" will have some instructions to apply for chef position.
* Login page will have two login options: email-password and google login. Facebook login is optional. Firebase authentication must have to be used.
* Register page will have a form containing username, email and password to register a new user.
* Events page will have some instructions to participate an event.
* Responsive and good design are mandatory.

### Back-End Part

* After login a new navigational menu will be added to the header name "Dashboard". 
* There will be two parts in the dashboard: user dashboard and admin dashboard.
* If a user logged in, only the user dashboard part will be shown in the dashboard page.
* If an admin logged in, only the admin dashboard will be shown in the dashboard page.
* From the dashboard, a user can cancel pending order, add rating, view chef training status and update profile picture with an image url.
* From the dashboard, a admin can change order status, cancel a order, set/change chef recruitment instructions, view chef training applications, set/change an event.

### Optional Tasks

* pagination, password recovery, password change, payment option

## Deploy
* Front-End app: Netlify/Firebase
* Back-End  app: Heroku