# FOODIENT
Food label scanner

## Overview
### Description
The app scans food labels and brings more in-depth information so the user knows what the ingredients in the label mean and how good/healthy it is.

### App Evaluation

- **Category:** health 
- **Mobile:** This app will be primarily developed for mobile 
- **story:** The app helps users to scan the label of the food they are buying
so they know if the food has too many chemicals and the problems these ingredients
can cause in the health in the short/long time. Like for example if the food 
is canceginours or has too many sugar.
- **Habit:** This can use as often as the user wants or feel the need to help
understand how unhealthy or healthy the food they are buying is. 
- **Scoope:** The idea is to be a free app that helps its users to understand 
better what is inside the food they are buying which helps to eat healthier and 
avoid health problems in the long run. 

## Product Spec
### 1. User Stories 

**Required must-have Stories** 

* User hits a button on introductory page to scan food product
* User can scan the barcode label on the product on the camera scanner page
* Info page where all the information about the contents of the product would be displayed in a table view

### 2. Screen Archetypes
* Main page with a button to scan the label
* Page with the scan camera to read the label
* Third page with the information about the label and possible break down of 
chemicals, too much sugar. 


### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Main page
* camera
* description page

**Flow Navigations** (Screen to Screen)

* Scan Now button - > Camera 
* Camera - > description page 


## Wireframes
<img src="https://i.imgur.com/HuaKAOr.jpg" title="source: imgur.com" /></a>

## Schema
### Models

### FoodItem

|     Property      |       Type        |          Description             |
|   -------------   |   -------------   |   ---------------------------    |
|     projectId     |     string        |   Unique id for the user post    |                 
|     ingredients   |     array         |   List of product ingredients    |
|     barcodeId     |     string        |   Barcode id of food item        |                 
|     Image         |     image         |   Image of product               |
|     Allergen list |     array         |   List of product allergens      |      
|     createdAt     |     DateTime      |   Date post is created           | 
|     updatedAt     |     DateTime      |   Last post update               |
