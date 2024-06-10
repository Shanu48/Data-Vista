---
# HTML for Beginners!

Lets get started!

---

## Why should you learn HTML?

- HTML: HyperText Markup Language

- It is the most basic building block of the Web

- It allows you to add/change website contents

- Its useful for:

  - Web developers
    
  - Software developers
      
  - Marketing Professionals
    
  - Sales
      
  - Business owners
      
  - Freelancers

---

## What do you need?

1. Web browser such as Chrome
2. Text Editor such as VS Code
---

## Getting started with VS Code

1. Go to this link to download the correct version of VS Code depending on your operating system. Link: [code.visualstudio.com](code.visualstudio.com)
2. Go to Extensions
   
   ![image](https://github.com/Shanu48/WebDev/assets/149718849/3c7eb6b0-29d2-4d9d-a1bf-eee2bc4b1cd8)

3. Download `Live Server`

   ![image](https://github.com/Shanu48/WebDev/assets/149718849/7b5a43b8-16d2-4a52-8f34-ecaf3ccd496e)

4. Create a new folder using the  `Explore Tab` and we can get started

---

## Creating your first page

1. Creat a file named `index.html`
2. Type in `<!DOCTYPE html>`. This is to let a reader know that this website uses HTML

> [!NOTE]
> 
> An HTML code contains tags. Tags are the key words that a webpage uses to define how a web browser will formate and display the contents
>
> They are enclosed in angle brackets `<>`
>
> They usually occur in pairs a **opening tag** and a **closing tag**

3. All the code is written within HTML tags
```
<!DOCTYPE html>

<HTML>

(Code comes here)

</HTML>
```

> [!NOTE]
> 
> There are two main parts: head and body
>
> The `<head>` tag contains information about the webpage
>
> The `<body>` tag contains what we want to display to the user

4. So lets create these two
```
<!DOCTYPE html>

<HTML>
  <head>
  </head>

  <body>
  </body>

</HTML>
```

> [!TIP]
> 
> Its nice to work the code as well as checking out the website side by side
> 
> To do so right click on the webpage name on VS Code and click `Open with Live Server`
> 
> Now arrange the website and VS Code side by side
> 
> Now, whenever you save a change on VS Code it will be directly reflected on the Web page


> [!TIP]
>
> You can change the browser in which the website opens
>
> Go to `File` > `Preferences` > `Settings`
>
> Under Extentions go to `Live Server Config`
>
> Change null under default browser to your your preferred browser

5. Lets now add a title to the website. Title is something that is at the top in the tabs. It comes under the `<head>` tag
```
<head>
  <title>My First Website</title>
</head>
```

### Headings

Its possible to add 6 sizes of heading in HTML

```
    <body>
        <h1>I like pizza!</h1>
        <h2>I like pizza!</h2>
        <h3>I like pizza!</h3>
        <h4>I like pizza!</h4>
        <h5>I like pizza!</h5>
        <h6>I like pizza!</h6>
    </body>
```

Output:

![image](https://github.com/Shanu48/WebDev/assets/149718849/3c4085b3-8212-42e2-96b6-6b4c881193d6)


> [!NOTE]
>
> Tags with content within them are known as elements
>
> Eg: `<h1>` this is a tag
>
> `<h1> Heading 1 </h1>` this is an element

---
### Paragraph Element

It is enclosed within `<p> </p>`

By default browser adds an empty line before and after this element

To create some sample texts type `lorem` within the `<p> </p>` tags and press tab

```
    <body>
        <p>This is some sample text</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur voluptatum nisi aspernatur tenetur aut doloribus debitis odit, repudiandae illo aperiam quisquam consequatur doloremque minus totam ex corrupti numquam porro nam!</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quae dolore adipisci et doloribus similique in sed molestiae quis vero optio explicabo blanditiis quam deserunt asperiores, quod sint facere autem nesciunt.</p>
    </body>
```

---
### Line Break

The line break `<br>` element is used to add a line break

There is no closing tag

---
### Horizontal line

Its used to seperate a webpage or partition it horizontally

Tag: `<hr>`

---
### Comments

These are not visible on the main website

They are added for the convinence of a reader

`<!-- This is a comment -->`

---
Everything that we did in this section is available in this VS Code file: [beginner1](https://github.com/Shanu48/WebDev/blob/main/HTML/beginner1.html)
---

## Hyperlink

Syntax:

```
<a href="link" target=(_self/_blank) title="A message"> Text you want to display </a>
```
Eg: 
```
<a href="www.google.com" target=_self title="this link takes you to google"> Google.com </a>
```

href: its used to insert the link of the target page

If your website has a second page which is present in the same folder then just put the name

Eg:

make another file named page2.html in the same folder as the index.html file. Insert basic html tags and add this line:
```
<a href="page2.html" target=_self title="this link takes you to another page"> Page 2 </a>
```

target: this attribute is used to determine whether you want to open the hyperlink in the same tab (_self) or in a new tab (_blank)

title: using this attribute you can display a message about the hyperlink when you hover over it

Hyperlink can also be used to email someone

In the href attribute, type mailto:(email address)

Eg:
```
<a href="mailto:abc123@gmail.com" target=_blank title="email me"> Email me here </a>
```

>[!TIP}
>In VS code, in a file with .html extention if you type ! and press tab then it automatically types down a basic html layout for you

---

## Inserting Images

>[!TIP]
>Keep the image in the same folder as the html file

Syntax:

```
<img src="name of the image">
```

>[!TIP]
>If your website has a lot of files then its adviced to keep the images in a seperate folder
>
>When we do this, we cannot just write the image name when giving the source (src), insted we need to write the path for the image relative to the html file using it
>
>You can find the path by right clicking on the image and going to properties
>
>If the iamge folder and the html file are in the same folder, then the source can be `src="/(folder name)/(image name)`

### Attributes

* height

* width

>[!NOTE]
>When you give just the height or only the width attribute then they change proportinately to each other
>
>When you give both of them, they change irrespective of each other

* alt: Alternative attribute is used to give an alternative text to the image. It is helpful to the people who use screen reader
* title: Its the text that is displayed when we hover over the image
* you can also use image as a hyper link. Just insted of the text that we put between the `<a> </a>` tag, put the image

---

## Audios in HTML

Syntax:
```
<audio src="audiofile.mp3"
```

There are some attributes that can be added. These are boolean attributes so you just need to type in the attribute if you need it else ignore
* controls: to add some controls
* autoplay: if you want the audio to start playing as soon as the website is opened
* muted: if you want the audio to be muted initially
* loop: if you want the audio to replay after the whole thing has been played

If you want to add additional or alternate sources:
```
<audio controls>
  <source src="audio.mp3">
  <source src="audio.wav">
  This browser does not support it
</audio>
```
---

## Videos in HTML

Just like images and audios, videos can also be added on a webpage

The video should be in `mp4`, `webM` or `Ogg` format

Syntax:
```
<video src="video.mp4">
```
OR (incase the web browser does not support the format
```
<video controls>
  <source src="video.mp4">
  <source src="video.WebM">
  This browser does not support it
</video>
```

### Attributes
* width
* height
* controls (boolean)
* autoplay (boolean)
* muted (boolean)
* loop (boolean)
  
---

## Text Formatting

`<b>bold</b>`

`<i>italic</i>`

`<big>big</big>`

`<small>small</small>`

`<sub>subscript<sub>`

`<sup>superscript<sup>`

`<ins>inserted<ins>`

`<del>deleted</del>`

`<mark>basically highlighted</mark>`

---

## Lists in HTML

There are three types of lists in HTML
1. Ordered list
2. Unordered list
3. Description list

### Ordered list

* Indicated by `<ol> </ol>` tags
* List items are kept between `<li> </li>` tags
* It has a type attribute to change the type of list
  * Syntax: `<ol type="1/A/a/I/i">`

### Unordered list

* Indicated by `<ul> </ul>` tags
* List items are kept between `<li> </li>` tags
* It also has types such as disc, circular, etc.

### Description list
* Indicated by `<dl> </dl>` tags
* It has two other tags
  * `<dt>`description term`</dt>`
  * `<dd>`description definition`<dd>`
* It can be used when you are trying to define or explain certain things
---

## Tables

>[!NOTE]
>Various types of lists can be nested within one another depending on your requirements


---
References:
[Video](https://www.youtube.com/watch?v=HD13eq_Pmp8)
