# Inventory Management System

## Overview
**SmartStocker** is a software application designed to help store operators efficiently manage electronic product inventory. It allows users to **add, update, remove, and search for products** in a centralized database.

We focused on establishing the core product data model and implementing fundamental CRUD (Create, Read, Update, Delete) functionality for inventory items, specifically the ability to add and remove products from the database. At its core the program performs the following.


-  **Product Database**: Add, update, and delete inventory items.

-  **Search & Filter**: Find products easily using search and filters, enhanced by AI.

-  **Admin Authentication**: Lock inventory modification behind a login system.

-  **Activity Logging**: Keep track of actions performed across the database.

## Noteable Features

- **Custom Fields**: Add custom fields to enhance efficiency of searching and user workflow.

- **Image/File Support**: Support for file types *png*, *jpg*, *jpeg*, *bmp*, and *gif*. Include any number of supported files with inventory items.

- **AI Assistant**: An assistant embedded in the programs dashboard powered by *Google Gemini 1.5 Flash* to assist with questions involving inventory.

- **Relevancy System**: If a traditional search yields no results, our relevancy system powered by *Google Gemini 1.5 Flash* will recommend inventory items relevant to what the user had searched.

## Embedded AI Assistant
In order to use the project's embedded artifical intelligence assistant, you must visit google's [ai studio](https://aistudio.google.com/app/apikey) and generate an API key. Then, navigate to python_/code/ai/AI.py and replace the commented code on line 16 with your generated API key.

## Collaborators 
- Nathan Tandory

- Myron Lobo

- Zayam Khan

- Derrin Manoj




