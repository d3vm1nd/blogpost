---
layout: "@Layouts/Layoutmd.astro"
title: HTML Structure
date: 20-01-2024
author: Demian Ruiz
desc: Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?
image: https://cdn.pixabay.com/photo/2015/12/04/14/05/code-1076536_1280.jpg
---

# Html Structure

![html](https://cdn.pixabay.com/photo/2015/12/04/14/05/code-1076536_1280.jpg)

Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?
Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?

Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?

Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?



```html
<!DOCTYPE html>
<html lang = "en-US">
  <head>
    <meta charset = "utf-8">
    <title>My test page</title>
    
    <style>
      form {
        margin : 0 auto;
        width: 400px;
        padding : 1em;
        border : 1px solid #CCC;
        border-radius : 1em;
      }
      
      ul {
        list-style : none;
        padding : 0;
        margin : 0;
      }
      
      form li + li {
        margin-top : 1em;
      }
      
      label {
        display : inline-block;
        width : 90px;
        text-align : right;
      }
      
      input, textarea {
        font : 1em sans-serif;
        width : 300px;
        box-sizing : border-box;
        border : 1px solid #999;
      }
      
      input : focus, textarea : focus {
        border-color : #000;
      }
      
      textarea {
        vertical-align : top;
        height : 5em;
      }
      
      .button {
        padding-left : 90px;
      }
      
      button {
        margin-left : .5em;
      }
      
    </style>
  </head>
  <body>
    <p>This is my page</p>
    <form action = "/my-handling-form-page" method = "post">
      <ul>
        <li>
          <label for = "name">Name:</label>
          <input type = "text" id = "name" name = "user_name">
        </li>
        
        <li>
          <label for = "mail">E-mail:</label>
          <input type = "email" id = "mail" name = 'user_mail'>
        </li>
        
        <li>
          <label for = "msg">Message:</label>
          <textarea id = "msg" name = "user_message"></textarea>
        </li>
        
        <li class = "button">
          <button type = "submit">Send your message</button>
        </li>
      </ul>
    </form>
  </body>
</html>

```
