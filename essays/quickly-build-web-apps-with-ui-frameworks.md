---
layout: essay
type: essay
title: "Quickly Build Web Applications with UI Frameworks"
# All dates must be YYYY-MM-DD format!
date: 2022-10-08
published: true
labels:
- Tailwind
- Bootstrap
- Learning
---
When students first start web development, they typically go through a curriculum that uses HTML, CSS, and Javascript to set their foundation. Raw HTML, CSS, and Javascript are useful for understanding the basics of DOM manipulation, however it can be quite tedious to write reusable code with those three alone. That’s where frameworks come in to help.

Working with HTML and CSS alone in particular can be a daunting task. Mobile responsiveness and styling elements are tricky to get right, and it can require a lot of lines of code. With UI frameworks such as [Bootstrap](https://getbootstrap.com/) or [Tailwind](https://tailwindcss.com/), a responsive web application can be up and running a lot quicker. On top of that, because they reduce the time that it takes to style or add responsiveness, more focus can be put on the complex logic behind the applications.

Here’s an example of Bootstrap vs. CSS:

<p class="codepen" data-height="300" data-default-tab="html,result" data-slug-hash="XWqPYKd" data-user="giorgio808" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/giorgio808/pen/XWqPYKd">
  Bootstrap Example</a> by Giorgio (<a href="https://codepen.io/giorgio808">@giorgio808</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>

<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<div>Bootstrap</div>
<br>
<p class="codepen" data-height="300" data-default-tab="html,result" data-slug-hash="QWrVxmW" data-user="giorgio808" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/giorgio808/pen/QWrVxmW">
  CSS example</a> by Giorgio (<a href="https://codepen.io/giorgio808">@giorgio808</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<div>Pure CSS and HTML</div>
<br>

### What UI framework should you choose?

Well that depends on the needs of the project. With a project that is heavy on the backend and logic, maybe using Bootstrap would be nice for the frontend side of it. Bootstrap has pre-made components that can be used to style HTML elements. A few of my favorites are the toggler collapsible navbar and the carousel. These two would probably require quite a few lines of CSS for implementation. However, the drawback of using Bootstrap is that projects can look similar to other sites that use Bootstrap. This could make the site look less original.

<div class="w-100 d-flex justify-content-center">
    <img height="200px" src="../img/quickly-build-web-apps-with-ui-frameworks/tailwind.png" alt="tailwind">
</div>

The other alternative to make a more customized site is Tailwind. This framework is really good especially when combined with React, since components can be quickly created. It is similar to Bootstrap in the sense that styling can be done via the class attribute in HTML (or className attribute in JSX). The con of Tailwind is that it makes everything look a bit more messy since everything is inline. Ultimately though, both Bootstrap and Tailwind are awesome frameworks that can be used to quickly develop a site’s UI compared to plain HTML and CSS. 
