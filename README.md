

--[Dsa Documentation (2).pdf](https://github.com/user-attachments/files/17357216/Dsa.Documentation.2.pdf)
-

# Phonebook Application

## Overview

The Phonebook Application is a robust desktop application built in Java using the Swing framework. Designed to manage contact information efficiently, this application provides an intuitive interface that enables users to perform essential contact management tasks. It emphasizes preventing duplicate entries and ensuring user-friendly interactions.

## Table of Contents

1. Features
2. Functionalities
3. Technologies Used
4. Installation
5. Usage
6. Efficiency Analysis
7. Contributors

## Features

- User-friendly interface for managing contacts
- Insert, search, update, delete, and display contacts
- Prevent duplicate phone numbers
- Sorting for efficient searching
- Dynamic contact viewing with action buttons for calling, texting, or video calling

## Functionalities

1. Insert Contact: 
   - Allows users to enter new contacts with fields for first name, surname, and phone number. 
   - Validates entries to prevent duplicate phone numbers and ensures formatting is consistent.

2. Search Contact: 
   - Implements a linear search algorithm to find contacts by their names or surnames based on user input. 
   - The search is case-insensitive and updates results in real-time as the user types.

3. Display All Contacts: 
   - Displays all contacts stored in the application in a list format.

4. Delete Contact: 
   - Users can select one or multiple contacts for deletion. 
   - Confirms deletion to prevent accidental loss of data.

5. Update Contact: 
   - Users can update the details of an existing contact, ensuring accurate and up-to-date information.

6. Sort Contacts: 
   - Contacts are automatically sorted alphabetically by first name and surname to enhance search speed and improve usability.

7. Efficiency Analysis: 
   - The search algorithm employed is a linear search, which traverses through the list of contacts. 
   - The time complexity is O(n) in the worst case, making it efficient for small to medium-sized contact lists.

## Technologies Used

- Java
- Swing (for GUI)
- Linked List (for contact storage)

## Usage

- Open the application to view the main interface.
- Use the Insert button to add new contacts. A dialog will prompt for the necessary information.
- Search for contacts using the search bar at the top.
- Select a contact from the list to view details and available actions (text, call, video call).
- Use the Delete button to remove selected contacts.
- Update existing contacts with new information as needed.

## Efficiency Analysis

The search functionality utilizes a linear search algorithm, which checks each contact one by one. While this method is straightforward, it becomes less efficient as the number of contacts grows. For contact lists exceeding a few hundred entries, the implementation of a hash table for storing contacts is recommended.

A hash table can provide average-case constant time complexity O(1) for search operations, significantly improving performance for larger datasets. In practical terms, this approach allows for faster retrieval and management of contacts, enhancing the application's responsiveness.

In the current design, the application remains effective for a maximum of 2000 contacts while ensuring that the user experience is smooth and efficient.
## Contributors

- Your Name
- Team Members: 
  - Ndilipawa Alweendo (223031488)
  - Isron E. Ndaningina (223031992)
  - Penehafo Nakale (223138339)
  - Jacinto C. Tchayevala (224084003)
  - Anesu A. Mwape (224044095)
  - Esegel S. Narib (223086770)
