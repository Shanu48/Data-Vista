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

## Hyperlinks


---
References:
[Video](https://www.youtube.com/watch?v=HD13eq_Pmp8)
