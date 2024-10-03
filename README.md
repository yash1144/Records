# Records Management Application

This is a simple **CRUD** (Create, Read, Update, Delete) web application built using **HTML**, **CSS**, and **JavaScript**. The app allows users to manage records, store them in the browser's **LocalStorage**, and perform basic operations like adding, editing, deleting, and searching for records.

## Demo Screenshot

![Screenshot 2024-10-03 115731](https://github.com/user-attachments/assets/9ebbd4a2-cf1c-46b3-a551-387e9a968ee0)


## Features
- Add records with **Name** and **Details**.
- Display stored records in a table format.
- Edit and update records.
- Delete records.
- Search records by name.
- All data is stored locally using the **LocalStorage API**.

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.).

### Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/yash1144/Records.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Records
    ```
3. Open `index.html` in a web browser:
    ```bash
    open index.html
    ```

### Usage
1. Enter a name and some details in the input fields.
2. Click on **Add Record** to store the data in LocalStorage.
3. Use the **Search** bar to filter records by name.
4. Edit or delete records using the action buttons provided in the table.

## Files Overview

- **index.html**: Main HTML structure of the application.
- **style.css**: Contains styles for the application layout, buttons, and table.
- **script.js**: JavaScript logic for handling LocalStorage operations (CRUD functionality).

## LocalStorage

The records are stored locally in the browser using LocalStorage, meaning the data will persist even after refreshing the page. However, the data is tied to the specific browser and device.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project as long as you include attribution to the original author.

## Contributing

Feel free to contribute to the project by submitting pull requests or reporting issues.

