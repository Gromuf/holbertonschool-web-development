## Resources

**Read or watch**:

- [Learn to Code HTML & CSS](/rltoken/D6o845Dj6bWanYggYGQK4A "Learn to Code HTML & CSS") (_until “Creating Lists” included_)
- [Introduction to HTML](/rltoken/pi2d_GWRubaTHQfAmKb8FQ "Introduction to HTML")
- [MDN](/rltoken/STnL1M-mwzCvnzHtG21XGQ "MDN")

## Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](/rltoken/tk1bYe9n6YmcEsF-gwOgMA "explain to anyone"), **without the help of Google**:

### General

- What is HTML
- How to create an HTML page from a wireframe
- What is a markup language
- What is the DOM
- What is an element / tag
- What is an attribute
- What the purpose of each HTML tag

## Requirements

### General

- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project is mandatory
- You are **not allowed** to install, import or use external libraries. This website must be build with only HTML/CSS/JavaScript. No NodeJS, React, VueJS, Bootstrap, etc.
- Your code should be W3C compliant and validate with [W3C-Validator](/rltoken/czWaAX6ZYwSLoR3bh2Qiqg "W3C-Validator")

## Tasks

### 1.

In this and coming projects, you will implement from scratch a webpage from a designer file.

For this first project, you will focus on the HTML structure only - **no CSS, no style - just pure HTML semantic.**

This designer file will be available on [Figma](/rltoken/ChJbK90Un6oS2A6ozdyTQA "Figma") - feel free to create an account to access the final result here:

- [Page in Figma](/rltoken/lhaBvvfXnyGKs9bRxokWtQ "Page in Figma")
- [fig file](/rltoken/BOC4LSHhGgn-RudlXjuUKg "fig file")

And “Duplicate to your Drafts” to have access to all design details.

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250808%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250808T081224Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4c1fcd456d9290cde1cefe0f50595efda0b0219906004bf948fd6a6cfed68b5d)

Important notes with Figma:

- if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](/rltoken/76O2REi_XN8esxhm9fZg9w "source-sans-pro") and [Spin-Cycle-OT](/rltoken/tIZuYvssJ291nB0BWUl-Tw "Spin-Cycle-OT")
- some values are in float - feel free to round them

For this task, please write an amazing `README.md`

### 2.

Let’s start at the top: **the header**

Here is the wireframe of it:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/f08f357fc2c894d821a29b7f907f26089ec68d86.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250808%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250808T081224Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e8d34bb0c1765a320c5ed0ce8304a0dad56d66374130e58bb4fcbb5280f752e0)

- Create the HTML skeleton (`html`, `head`, `body`, etc.)
- In the body, add a `header` tag
- Inside this `header`:
  - Add a link element with an image inside
  - Add a block of 3 link elements

### 3.

Now, the banner inside the `main`:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/d3f0dba16af368a681919fb44306fadfb2499b54.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250808%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250808T081224Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e89bdd5788e3237192f205427d8d4c456deefd68944eeba16f25454de9bd6daa)

Add a `main` tag that has a `section` element inside.

In this `section` element, add:

- A block containing:
  - A heading tag (level 1, don’t forget to use the correct heading value)
  - A text element
  - A button tag
- Another block containing:
  - Another heading tag (level 2, be careful about which one you are using)
  - A block containing 4 blocks - each block containing:
    - An image
    - A heading tag (level 3)
    - A text

### 4.

Under the banner, we will add the quote block:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/e898eac85272d52f5528ea81678000045a37017a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250808%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250808T081224Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ab231e87e6d2ab78e83ebcfaa4957bb2e8189f0345141102b332997964eb0796)

The quote section is inside the `main`:

- Create a new `section` for the quote
- Inside, add a block containing:
  - An image
  - Another block with inside:
    - A blockquote tag
    - A text tag for the quote author
    - Another text

### 5.

Let’s now add the videos list:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/a5712ac70330c6812c6aee2bf21efe7ac53d1397.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250808%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250808T081224Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fd9d99b68b1f2bf41987887b0c7eaf1f78c0f039169420982348d284656ff5af)

New `section` containing:

- A heading tag (level 1)
- A block containing the 4 video blocks - each of them are composed with:
  - An image
  - A heading (level 2)
  - A text
  - Add a block for the author information:
    - An image
    - A heading (level 3)
  - A block for the rating:
    - A block of images (one star = one image)
    - A text

### 6.

The Membership section is similar to the videos list:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1ddf18bc6d89725de2fde4881e8990fae6d89628.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250808%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250808T081224Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=227141adf3311e673db4698cf1f1b70c4d4ebf057c072bda57a651440b1c21a2)

After the videos list section, add a new `section` containing:

- A heading (level 1)
- A block containing 4 block items - each block containing:
  - An image
  - A heading (level 2)
  - A text
- A button

### 7.

The FAQ section is ending the page before the footer:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/e4b2806abe9edc126fa0d4155aaf5d7e7da479e4.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250808%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250808T081224Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=eea87ef99a658eacf045a5ea382555b3217e8d73c9d72e1455a35d73150032eb)

Add a `section` for the FAQ containing:

- A heading (level 1)
- A block that contains 2 “row blocks”
- Each “row block” contains 2 “item blocks”
- Each “item block” is composed of:
  - A heading (level 2)
  - A text

Hint: There is no “row block” tag, “row” is referring to the styling that will be applied in a future project. It just means two “rows” containing two “items” each, also containing their own elements.

### 8.

And… the footer!

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/7224527ac842981b3b387cd9d713b4a1b912a487.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20250808%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20250808T081224Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a69a7cc2a167281816a6a27b410c541e2da31c0f1e66290efe3d21bd7d6fd396)

After the last `section`, outside of the `main`, add a `footer`:

- A block (used later for centering the footer content), inside this block:
  - Another block with:
    - An image
    - Another block containing:
      - 3 Images with link
  - A text

And… that’s it for the moment - the result should not be shiny, don’t worry, CSS is coming…

### image of a part of the result :

![alt text](image.png)
