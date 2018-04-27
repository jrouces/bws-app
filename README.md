# bws-app

Simple static web app for creating Best-Worst Scaling annotations. It consists of two parts:

- content-generator: Java application that takes information from the elements to annotate and auto-generates HTML code with the tuples, which is meant to be pasted inside the main HTML file in web-app.
- web-app: HTML+JS front end, wherein the output of content-generator should be pasted.
