---
layout: "@Layouts/Layoutmd.astro"
title: CSS Structure
date: 20-01-2024
author: Demian Ruiz
desc: Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?
image: https://cdn.pixabay.com/photo/2016/11/23/14/45/coding-1853305_1280.jpg
---

# CSS Structure

![html](https://cdn.pixabay.com/photo/2016/11/23/14/45/coding-1853305_1280.jpg)

Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?
Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?

Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?

Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis numquam voluptate obcaecati, fugiat consequuntur debitis quos. Fugit, delectus aut officiis eos voluptate accusamus enim, consectetur quas illo nemo eaque iure?



```css
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

```
