# Homework for week1 

***Version 1.0.1 Date 08/07/21***

In this project, I modified some HTML tags, gave it a concise, descriptive title, added alt for img tags and add an id to make the Search Engine Optimization link work. 

## User Story

* As a user, I want the image to have an alternate text, so that I can read if the image is not displayed.
* As a user, I want to easily navigate to any sections with quick links on the navigation bar.

## Acceptance Criteria

1. It's done when the page uses semantic HTML elements. Change div to `header`, `main`, `article`, `nav`, and `footer`.

```
Change <div to <header class="header">
```

2. It's done when the header and footer are fixed to the top and bottom of the webpage.

```
.header { 
  position: fixed;
}
```

3. It's done when, if the links on the header are clicked, the page jumps directly to the right section.

```
 id="search-engine-optimization"
```

4. It's done when the image includes a descriptive `alt` attribute.

```
 <img src="./assets/images/search-engine-optimization.jpg" alt=" search engine optimization" class="float-left" />
```
5. It's done when the `Class` in CSS file are unified, as they apply to the same style.

*Combine .benefit-lead .benefit-brand .benefit-cost to `benefit-seciton`* 

```
.benefit-section {
  margin-bottom: 32px; color: #ffffff;
}
```
*Combine .search-engine-optimization .online-reputation-management .social-media-marketing to `content-section`*

```
.content-section {
  margin-bottom: 20px;
  padding: 50px;
  height: 300px;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  background-color: #0072bb;
  color: #ffffff;
}
```

## Others for look and feel enhancement (UX)

* Adjusted the length of `benefits` part to make it looks the same length as `content` part.

```
.benefit {
    height: 75em;
}
```
* Adjusted the margin for `content` and `benefit` to center both in webpage for a better look.
```
  .Content {
  margin-left: 1.9em;
  }

  .benefit {
    margin-right: 1.9em;
  }
```

![index.html screenshot](./screenshot/website.png)


[Click me for website](https://mt0814.github.io/Homework-week1/)

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.