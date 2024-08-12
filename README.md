# HTMX Contacts App

## Overview

This Contacts App is a simple yet powerful tool for managing your contacts. It comes from the [Hypermedia Systems](https://hypermedia.systems/) book and is built using **HTMX** for a dynamic and responsive user interface and **Flask** as the backend framework. This app provides a seamless experience for adding, editing, and managing your contacts efficiently, and serves as an effecive example of the power of **HTMX** for creating modern web applications using SSR and hypermedia.

## Features

- **Add Contacts:** Easily add new contacts with a simple form.
- **Edit Contacts:** Update contact information directly from the contact list.
- **Delete Contacts:** Remove contacts with a single click.
- **Search Contacts:** Quickly find contacts by name or other details.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies Used

- **HTMX:** Handles client-side interactivity and partial page updates without the need for full page reloads.
- **Flask:** A lightweight web framework that provides the backend for managing the data and API endpoints.
- **HTML5 & CSS3:** For creating a clean and responsive user interface.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sjuarezsd/htmx-contacts-app.git
    cd htmx-contacts-app
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application:**

    ```bash
    flask run
    ```

5. **Access the app:**
   Open your web browser and go to `http://127.0.0.1:5000/` to start managing your contacts.

## Usage

1. **Adding Contacts:** Click the "Add Contact" link and fill out the form with the contact's details.
2. **Editing Contacts:** Click the "Options" button, then the "Edit" button next to a contact's entry, modify the information, and save changes.
3. **Deleting Contacts:** Click the "Options" button, then the "Delete" button to remove a contact from the list.
4. **Searching Contacts:** Use the search bar at the top to find specific contacts quickly.

## Acknowledgements

- **HTMX**: For enabling a smooth, interactive front-end experience without relying on heavy JavaScript.
- **Flask**: For being a simple yet powerful backend framework.

---

**Author**: [Steven Juarez]