# PageLogin
![Screenshot from 2024-10-29 11-25-44](https://github.com/user-attachments/assets/3e9b607a-ddf7-4085-aa84-d9f097630ba4)

This document describes a simple HTML structure for a login page. The page allows users to log in using their username and password.

## Overview

The login page is designed with a clean layout and includes a form where users can enter their credentials.

## Structure

1. **Head Section**:
   - Links to an external stylesheet (`style.css`) for styling.
   - Sets the document character encoding to UTF-8 for proper text display.
   - Includes a viewport meta tag for responsive design on various devices.
   - Specifies compatibility with Internet Explorer.
   - Contains an author meta tag.

2. **Body Section**:
   - Contains a form with the class `box`, which styles the form element.
   - A heading (`<h3>`) to indicate the purpose of the page.
   - Input fields for username and password:
     - **Username**: A text input field with a placeholder indicating that it can be an email or name.
     - **Password**: A password input field with a placeholder for the password.
   - A button labeled "Log In" for submitting the form.
   - A footer section displaying the server's name or handle.

## Example HTML Structure

```html
<!DOCTYPE html>
<html>
<head>
    <link rel='stylesheet' href='style.css'>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <meta name='author' content='Log in'>         
    <title>Log in</title>
</head>
<body>
    <form class='box'>
        <h3>Login Here</h3>
        <label for='Username'>Username</label>
        <input type='text' placeholder='Email or Name' id='Email'>
        <label for='Password'>Password</label>
        <input type='password' placeholder='password' id='pass'>
        <button>Log In</button>
        <
