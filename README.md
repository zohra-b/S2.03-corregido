<p align="center"><h1 align="center">S2.03 - MongoDB Structure </h1></p>

<br>

---

## 📍 Objectives

Learn to model noSql databases.
---

## 👾 Exercises

### 📌 Level 1 

An optician, called “Cul d'Ampolla”, wants to computerize the management of customers and sales of glasses.

First of all, the optician wants to know who the supplier of each pair of glasses is. Specifically, it wants to know about each supplier: The name, the address (street, number, floor, door, city, postal code and country), telephone, fax, NIF.

About the glasses, it wants to know: The brand, the prescription of each lens, the type of frame (floating, paste or metal), the color of the frame, the color of each lens and the price.

About the customers, it wants to store: The name, the postal address, the phone, the email, the date of registration.
When a new customer arrives, store the customer who recommended the establishment to them (provided that someone has recommended them).
Our system must indicate who the employee who sold each pair of glasses was. Defines what day/time the sale takes place.

    -  ### Level 1 - Exercise 1
Imagine we have the following graphical interface, from the point of view of an Optician customer. How would you design the database that would facilitate the information?
![image](https://github.com/user-attachments/assets/a2e45d43-b361-4f8b-8e57-8e6af19a0049)

    - ### Level 1 - Exercise 2
What if the point of view was the interface and the glasses were the same?
![image](https://github.com/user-attachments/assets/337206ca-cdc3-41b1-87e4-140eccf5b6b4)

  

### 📌 Level 2 
    
You have been hired to design a website that allows you to order food online.
Consider the following guidelines to model what the project database would look like:
For each customer, we store a unique identifier: Name, surname, address, postal code, city, province, telephone number.
A person can place many orders, but a single order can only be placed by a single person. 
A unique identifier is stored for each order: Date/time of placement, whether the order is for home delivery or for collection in a store, the quantity of products selected of each type, the total price, and a note with additional information.
An order can consist of one or more products.
The products can be pizzas, hamburgers, and drinks. A unique identifier is stored for each product: Name, description, image, price. In the case of pizzas, there are several categories that may change their names throughout the year.
An order is managed by a single store and a store can manage many orders. A unique identifier is stored for each store: Address, postal code, town, province.
Many employees can work in a store and an employee can only work in one store. A unique identifier is stored for each employee: Name, surname, NIF, Telephone number, if they work as a cook or delivery person. For home delivery orders, it is important to store who the delivery person is who delivers the order and the date/time of delivery.
Design a system in which a Stock Broker (Observable) notifies several Stock Brokers (Observers) of changes when the Stock Market goes up or down.
It is necessary for the Observable object to maintain references to the Observers.
![image](https://github.com/user-attachments/assets/eef8b1a9-35fc-40a8-bd4e-2ca25c389dd3)



### 📌 Level 3 

We will try to make a simple model of what the database for a reduced version of YouTube would be like.
For each user we store a unique identifier: Email, password, username, date of birth, gender, country, postal code.
A user publishes videos. For each video we store a unique identifier: A title, a description, a size, the name of the video file, the duration of the video, a thumbnail, the number of views, the number of likes, the number of dislikes.
A video can have three different states: public, hidden and private. A video can have many tags. It is interesting to store who the user is who publishes the video and what date/time they do it.
A user can create a channel. A channel has a unique identifier: A name, a description, a creation date.
A user can subscribe to the channels of other users. A user can like or dislike a video only once. It will be necessary to keep a record of the users who have liked and disliked a given video and the date/time they did so.
A user can create playlists with the videos they like. Each playlist has a unique identifier: A name, a creation date, a status indicating whether it can be public or private.
A user can write comments on a given video. Each comment is identified by a unique identifier: The text of the comment, the date/time it was made.
![image](https://github.com/user-attachments/assets/8a7d68be-a84b-4e1e-bbcb-410e3dc0e81d)

---
## 🚀 Getting Started

### ☑️ Prerequisites

Before getting started with S2.03, ensure your runtime environment meets the following requirements:

- **Programming Languages
- an IDE : IntelliJ / Eclipse IDE / VScode
- MongoDB v8.0.8


### ⚙️ Installation

Clone the S2.03 repository:
```sh
❯ git clone https://github.com/zohra-b/S2.03
```
