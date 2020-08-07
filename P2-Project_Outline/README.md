# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview

My capstone project will be a book subscription app. The origins of this project come from my time working at an independent bookstore and running a subscription service all by hand. Customers would purchase 3, 6, or 12 month subscriptions and each month they would receive a book in the mail. The drawbacks of doing it by hand meant that more mistakes could be made, that nobody else could really manage the subscription service but me, and that changes to the master list took more time. 

The benefits of creating an app for this kind of service would mean all the data would be housed somewhere safe (in an RDBMS like MySQL), so that when you are ready to send out the book for that month, you could run a function to display all current subscribers and print labels for USPS mailers. A simple UI would also mean multiple people could easily learn how to run the service any given month with little training. Ultimately, an app like this could be used for any type of subscription service (e.g. wine, flowers, magazines, etc.), but mine will pertain exclusively to books. 

It may make more sense for this app to take information directly from the customer, but I am simplifying for the time being. The app assumes a bookseller has either taken the customer's information by phone or received it over the web and charged the customer accordingly. Background: most independent bookstores must use ABA approved sites if they want to sell books online through a wholesaler, which helps streamline book sales. You can create custom products on their templates, but to my knowledge a subscription component doesn't yet exist. If it does, let's pretend it doesn't for the sake of my capstone...

### Features

1. Authentication: Bookstore owners will be able to create an account, log in, and manage their customers' data all in one place. The app would not be store-specific, meaning multiple bookstore owners could all use the app seamlessly. 

2. Input Data: After logging in, bookstore owners will be able to input a customer's information into the app and save it to an RDBMS. Customer information must include appropriate fields for their name, shipping address, phone number, email address, and length of subscription. 

3. View Data: At any given time during the month, bookstore owners must be able to log in and quickly view the customers who are current. The view should only include their name and shipping address, so that information could quickly be copied into a shipping app like Stamps.com. 

4. Search Data: A search function should be built for bookstore owners, so that when customers call and want to check on the status of their subscription, for instance, you can find their information quickly. Should there be a customer-facing component to this, where customers have view only privileges and could do this themselves? 

5. Alerts: There should be a feature built in where bookstore owners can easily see which of their subscribers are going to lapse and decide what action to take. This could involve incorporating some JavaScript into the app in order to differentiate certain customer data. 

### Technologies

1. Java
2. Spring Boot
3. Bootstrap
4. MySQL 
5. JavaScript
6. Hibernate
7. Thymeleaf 

### What I'll Have to Learn

As stated in the fifth feature outlined above, I will have to learn how to differentiate customer data in order to show the user which subscriptions are going to lapse. I imagine I will have a better understanding of how to approach this problem once I have the basics of the app down pat. Once I have the features above finished, I would like to explore how to work with an API to potentially read in book data. I regard this right now as an "extracurricular" as the app is not dependent on this tech, but it could be a fun feature if I can learn how to build it. 

### Project Tracker

[My Trello Board](https://trello.com/b/KZINYRVG/capstone)
