---
layout: project
type: project
image: img/specialty-coffee/specialty-coffee-square.png
title: "Specialty Coffee Oahu"
date: 2022
order: 4
published: true
labels:
  - React
  - Tailwind
  - MongoDB
  - Express
  - Google Maps Platform API
  - Github
summary: "A personal CRUD blog-like application that I am working on."
---

As a coffee lover, I wanted to create an application that would allow me to document the coffee shops that I visited in Oahu. With my previous Phonebook project, I gained experience on full-stack development. Specialty Coffee Oahu builds off from that knowledge and explores other elements of web development.

One of the main features of this project is that it uses the <a class="md" href="https://developers.google.com/maps/documentation/embed/get-started" target="_blank" rel="noopener noreferrer">Maps Embed API</a> from the <a class="md" href="https://developers.google.com/maps/apis-by-platform" target="_blank" rel="noopener noreferrer">Google Maps Platform</a>. This API is used to show the coffee shop's location on the map. The setup process on Google's end was quite straightforward since the platform had good documentation. However, the tricky part was getting the API key to be accessed as an environment variable. With Create React App in particular, the environment variable must be named <a class="md" href="https://create-react-app.dev/docs/adding-custom-environment-variables/" target="_blank" rel="noopener noreferrer">REACT_APP_NAMEOFVARIABLE</a>. The API URL can take in the name and location of the coffee shop. Through an HTTP request, it retrieves the specified place and shows it on a map. 

My CoffeeShopInfo component that uses the Google Maps Embed API:
<script src="https://gist.github.com/giorgio-tran/2f4ef634abc14c5dc99736bc974ea717.js"></script>

For styling, I decided to use Tailwind instead of pure CSS. Since React is component based, inline styling seems to be appropriate. I chose this framework over Bootstrap because it is more flexible when it comes to creating custom designs.

This project is still in the works and it has not been deployed yet. I am thinking of deploying it either via Vercel or Netlify since Heroku will no longer be free in November. That aside, feel free to check out the source code down below!

<img src="/img/specialty-coffee/specialty-coffee-browser.png" alt="specialty-coffee" class="container-fluid"/>

Source: <a class="md" href="https://github.com/giorgio-tran/specialty-coffee-oahu/" target="_blank" rel="noopener noreferrer">&nbsp;giorgio-tran/specialty-coffee-oahu</a>
