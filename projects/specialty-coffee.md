---
layout: project
type: project
image: img/specialty-coffee/specialty-coffee-square.png
title: "Specialty Coffee Oahu"
date: 
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

One of the main features of this project is that it uses the [Maps Embed API] from the [Google Maps Platform](https://developers.google.com/maps/apis-by-platform). This API is used to show the coffee shop's location on the map. The setup process on Google's end was quite straightforward since the platform had good documentation. However, the tricky part was getting the API key to be accessed as an environment variable. With Create React App in particular, the environment variable must be named [REACT_APP_NAMEOFVARIABLE](https://create-react-app.dev/docs/adding-custom-environment-variables/). The API URL can take in the name and location of the coffee shop. Through an HTTP request, it retrieves the specified place and shows it on a map. 

For styling, I decided to use Tailwind instead of pure CSS. Since React is component based, inline styling seems to be appropriate. I chose this framework over Bootstrap because it is more flexible when it comes to creating custom designs.

This project is still in the works and it has not been deployed yet. I am thinking of deploying it either via Vercel or Netlify since Heroku will no longer be free in November. That aside, feel free to check out the source code down below!


Source: <a href="https://github.com/giorgio-tran/odin-sketch/" target="_blank" rel="noopener noreferrer">&nbsp;giorgio-tran/odin-sketch</a>
