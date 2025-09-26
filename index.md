---
layout: default
title: Car City Sales Management System
---

# Car City Sales Management System

## Table of contents

* [Overview](#overview)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Continuous Integration](#continuous-integration)
* [Walkthrough videos](#walkthrough-videos)
* [Example enhancements](#example-enhancements)
* [Team](#team)

## Overview

Car City Sales Management System is an application designed for the fictional dealership Car City. It enables efficient management of customers, employees, vehicles, repairs, and transactions. The system provides full functionality to add, edit, and delete records, ensuring the dealership can seamlessly track and organize every aspect of its operations.

### Key Features

* Manage customers, employees, vehicles, repairs, and transactions in one system.
* Add, edit, and delete records to keep information accurate and up to date.
* Track car sales and service history for better customer support.
* Maintain organized employee and customer databases.
* Streamline dealership operations by connecting sales, service, and management functions.

### Purpose

Car City Sales Management System was created to simulate how a dealership manages its day-to-day operations. The application provides tools to organize records, track important business activities, and ensure smooth communication between departments. By integrating sales, repairs, and personnel management, Car City is able to operate more efficiently and provide better service to customers.

## User Guide

This section provides an overview of Car City Sales Management System's main features and how dealership admin can interact with the system.

### Landing Page

The landing page displays the application's name and purpose.

![](images/landing-page.png)

### Recipe Search and Filters

The recipe search page allows students to explore a variety of meals and snacks, with filters for dietary restrictions and ingredient availability. Each recipe page includes:
- Step-by-step instructions
- A list of ingredients, prices, and sources
- Dietary tags (e.g., vegan, gluten-free)
- Estimated preparation time and servings

![](images/recipe-page-1.png)

![](images/recipe-page-2.png)

![](images/recipe-page-4.png)

### Vendor Contributions

Local vendors can create profiles to list available ingredients, prices, and sizes, which helps students easily find the ingredients they need nearby.

### Admin Dashboard

Admins have additional privileges, such as approving or editing recipes, managing vendor contributions, and ensuring the quality of user-generated content.

## Community Feedback

We welcome feedback from the College Cooking community! Please share your experiences and suggestions to help us improve the application through our [Feedback Form](https://forms.gle/feedback-link).

## Developer Guide

This section provides developers with information on setting up, deploying, and maintaining College Cooking.

### Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory and install dependencies with:
   ```bash
   npm install

   createdb collegecooking

   npx generate

   npx migrate dev

   npm run dev 


#### ESLint

BowFolios includes a [.eslintrc](//eslintrcfile) file to define the coding style adhered to in this application. You can invoke ESLint from the command line as follows:

```
npm run lint
```

ESLint should run without generating any errors.

It's significantly easier to do development with ESLint integrated directly into your IDE (such as IntelliJ).

## Milestones

The objective of Milestone 1 was to design HTML mockups representing the core pages of the BowFolio system. This milestone provided a visual structure and helped plan the layout and navigation.

Milestone 1 was managed using [College Cooking Milestone Board M1](link):

![](images/project-board-1.png)

### Milestone 2: Data model development

In Milestone 2, we focused on developing the data model, which included setting up MongoDB collections and implementing the operations required to support BowFolio’s functionality. This step was crucial for the backend infrastructure, enabling data storage, retrieval, and management within the application.

Milestone 2 was managed using [College Cooking Milestone Board M2](link):

![](images/project-board-2.png)

## Milestone 3: Final touches

The purpose of Milestone 3 was to polish the codebase, address any remaining UI issues, and ensure a smooth user experience. This final pass involved debugging, enhancing styling, and improving overall functionality.

Milestone 3 was managed using [College Cooking Milestone Board M3](link):

![](images/project-board-3.png)

As of the time of writing, this screenshot shows that there is an ongoing task (i.e. this writing).



## Team

College Cooking is designed, created and built by [Anaya Cole](https://anayaemily.github.io/), [Lindsey Clement](//insert link), [Christina Holthe](https://chrshol.github.io/) and [Kayla Young](https://kaylay04.github.io/).