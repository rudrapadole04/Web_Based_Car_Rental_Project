
<h1 align="center">Web_Based_Car_Rental_Project</h1>  

This is a project for a car rental website. It is a project for the College Mini Project.

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Database](#database)
- [Table](#table)
- [Car Listing Page](#car-listing-page)
- [User Story](#user-story)
- [Admin Page](#admin-page)
- [Project Report](#project-report)
- [Authors](#authors)



## Introduction

- This is a car rental website project.
- The purpose of this project is to create a car rental website.
- The website will have a login page, a car listing page, a car reservation page, and a car return page.
- The login page will have a username and password input field.
- The car listing page will have a search bar and a car listing table.
- The car reservation page will have a car reservation table.

## Requirements

- XAMPP is required to run the project.
- The project will be hosted on a localhost server.

##  Installation

- Install XAMPP.
- Open XAMPP and click on the Start button.
- Clone the project to the root of the XAMPP server.
- Open the project in XAMPP.
- Import SQL file from database folder to the XAMPP server.
- Open Browser and navigate to [localhost:8080](localhost:8080).
- Hurray! The project is now running.

##  Database

- The database is stored in a folder called database.
- The database is named as carproject.sql.
- The database is stored in the root of the XAMPP server.
- The database is imported to the XAMPP server.
- Database used is MySQL.
- Database Connection page is named [connection.php](/connection.php).

## Table

- The table is named as car.
- The table has the following columns:
    - car_id: INTEGER PRIMARY KEY AUTO_INCREMENT
    - car_make: VARCHAR(255)
    - car_model: VARCHAR(255)
    - car_year: INTEGER
    - car_color: VARCHAR(255)
    - car_price: INTEGER
    - car_available: BOOLEAN
    - car_image: VARCHAR(255)
    - car_description: VARCHAR(255)

##  Car Listing Page

- The car listing page will have a search bar and a car listing table.
- The search bar will have a search button.
- The search button will search for the car based on the search bar input.
- The car shown only on the car listing page will be the car that is available.

## User Story

- As a user, I want to be able to search for a car.
- As a user, I want to be able to see the car that is available.
- As a user, I want to be able to reserve a car.
- As a user, I want to be able to return a car.
- As a user, I want to be able to see the car that I have reserved.
- As a user, I want to provide feedback to the car rental website.
- As a user, I should be able to make payment for the car rental.

## Admin Page

- The admin page will have a car listing table.
- It has a button to add a new car.
- The button will open a new page where the admin can add a new car.
- The admin can add a new car by filling in the form.
- The admin can also delete a car by clicking the delete button.
- Admin can view user reservation by clicking the view button.
- Admin can view user return by clicking the view button.
- Admin can accept or reject a reservation by clicking the accept or reject button.
- Admin can return a car by clicking the return button.
- Admin can delete a reservation by clicking the delete button.
- Admin can view feedback by clicking the view button.

## Project Report

- The project report is stored in a folder called [report](https://github.com/rudrapadole04/Web_Based_Car_Rental_Project/blob/main/report/Web_based_car_rental_report.pdf).
- Report consists of the following:
    - Introduction
    - Literature Review
    - Methodology
    - Result
    - Conclusion
    - References
- The project report is written in Microsoft Word.
- The project repot has flow chart, ERD, and UML diagram.


## Author 

- [Rudra N Padole](https://github.com/rudrapadole04)
