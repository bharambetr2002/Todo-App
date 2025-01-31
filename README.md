# TO-DO APP 

## Overview

This project is a simple list management application built using JavaScript. Users can add items to a list and remove them dynamically by clicking a delete button.

## Features

- Add items to a list by entering text and clicking the button.
- Prevents adding empty or invalid items.
- Dynamically create and append delete buttons for each list item.
- Remove individual list items by clicking the corresponding delete button.

## How It Works

The application follows this logic:

1. The user types text into the input field and clicks the "Add" button.
2. The program checks if the input is not empty.
3. If valid, a new list item (`<li>`) with a "Delete" button is created and added to the list.
4. Clicking the "Delete" button removes the corresponding list item.
