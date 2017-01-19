---
layout: post
title:  "Getting Started with Web Design"
date:   2017-01-07 23:07:12 -0500
categories: jekyll update
---

### <a name="getting-started"></a>Getting Started
To write our HTML, CSS and JavaScript Code, we will be using a popular text editor called [Sublime Text](https://www.sublimetext.com/3). This is a good, simple text editor that supports many different languages and comes with automatic code completion.

### <a name="install-sublime"></a>Installing Sublime Text
On the download page, choose the option for the machine you are working on and wait for it to download. After the installer is finished downloading, open it and follow the steps provided.

### <a name="creating-html-document"></a>Creating a HTML Document
Once you're in Sublime Text, save your file with a .html extension (Ex. index.html). After your file is saved, start with the basic layout of an HTML page. Your page should start with <!DOCTYPE html> which will tell your web browser which type of document it is working with. You should then include a ```<html>``` tag which shows the beginning of the html document followed by the ```<head>``` and the ```<body>```. Don't forget to close all of your tags. The snippet below shows the basic layout for a HTML page.  

To open your document, navigate to where you saved the file and double click to open it.

```html
<!DOCTYPE html>
  <html>
      <head>

      <head>
      <body>

      </body>
  </html>
```
### <a name="html-elements"></a>HTML Elements
####Title
The ```<title>``` tag can be used to give your webpage a name. The title is the text that appears on the tab in your web browser. The title tag should be included inside your head. You can see an example below.
```html
<head>
    <title>My New Page</title>
</head>
```
####Paragraph
The ```<p>``` Tag is used to create a paragraph. This is text that will be displayed on your web page. You can put whatever text you want inside your paragraph.This tag should be inside of the body.
```html
<body>
    <p>Writing HTML code is a lot of fun!</p>
</body>
```
####Images
The ```<img>``` tag can be used to add images to your web page. You can include any image you want on your page. The example below will show how to add an image you found on the internet by using it's URL. The image's SRC should be a link to the image. Similar to the paragraph, this tag should also be included in the body.
```html
<body>
    <img src='http://www.google.com/myFirstImage.jpg'>
</body>
```
####Links
Using the ```<a>``` tag, you can limk to any other page on the internet. You can do this by finding a page's url and including it as the href in your tag. You should include the text that you want to be displayed on your web page between the opening and closing ```<a>``` tag. This tag will also be found in your body.
```html
<body>
    <a href="http://www.google.com">Click me to go to Google!</a>
</body>
```
###<a name="css"></a>CSS
If you wish to add "style" to your website, you must use CSS. CSS is used to change the colors, backgrounds, fonts, etc. of a website. Your CSS should go inside of ```<style>``` tags which will be found inside the ```<head>```
```html
<head>
    <style>
        {YOUR CSS HERE}
    </style>
</head>
```
####Selecting Elements
To apply styles to a certain type of tag, using CSS you give the type of element and put the style for that type of element inside of clurly braces "{}". The example below is applying styles to all of the ```<p>``` tags.
```html
<head>
    <style>
        p{
          {PARAGRAPH STYLES HERE}
        }
    </style>
</head>
```
####Color
To change the color of an element you can change the color of elements by folowing the example below.
```html
<head>
    <style>
        p{
          color:red;
        }
    </style>
</head>
```
This example will change the color of all the ```<p>``` elements to red. 
####Backgrounds
You can change the background of an element using background-color or background-image. The example below shows how to change the background of your webpage to a solid red.
```html
<head>
    <style>
        body{
            background-color: red;
        }
    </style>
</head>
```
This will allow you to change to color of your background.
Adding an image of the background of your page is very similar to chaging the color. With a background image, you need to provide the url of your image. This can be seen in the example below.
```html
<head>
    <style>
        body{
            background-image: url('http://www.google.com/myBackgroundImage');
        }
    </style>
</head>
```
###<a name="javascript"></a>JavaScript
JavaScript is used to add dynamic (changing) content to your web page. JavaScript is a great tool for manipulating a page's content and the styles of that content.
####Learning more about Javascript
You can find some great JavaScript Tutorials on [W3Schools](http://www.w3schools.com/js/default.asp).

###Learning More
If you're interested in learning more about web design, two great resources are listed below.
####[W3Schools](http://www.w3schools.com/)
####[Codecademy](https://www.codecademy.com/learn/web)
