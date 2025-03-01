# V School Assignment - Color grid from scratch

## Summary of Steps to Complete (See corresponding sections below.)

- [x] Fork this assignment so you can work on your own copy.
- [x] Build the page file(s) in VSCode or an IDE of your choice.
- [x] Push your changes back to your GitHub repository.
- [ ] Turn on GitHub pages for your repository so your site can be viewed in a browser directly.
- [ ] Turn in a link to your GitHub repository and your GitHub Pages site for this assignment in Canvas.

## Link to assignment description

https://coursework.vschool.io/color-grid-from-scratch/

## Turn on GitHub Pages

This tutorial shows how to turn on GitHub Pages: Getting Started with GitHub Pages (12 min) https://www.youtube.com/watch?v=QyFcl_Fba-k

You don't need to complete all the steps of this tutorial. You really only need to push the pages you create to your main repository (time index 02:20) and turn on GitHub Pages in the settings (time index 03:22). The rest of it is a great demonstration of how to use branches in your projects and how to use different branches to host a site should you ever want to try that in the future.

* 00:00 Introduction 
* 00:47 Create a new GitHub repository (you can skip this since you already have one) 
* 01:10 Clone your repository (create a copy on your computer)
* 01:47 Create an index.html file
* 02:20 Push index.html to GitHub main branch
* 03:22 Turn on GitHub Pages in Settings
* 04:05 Find the url for your GitHub Pages site
* 04:38 Create a new branch to make changes
* 05:39 Push changes to your new branch to GitHub
* 06:12 Make a pull request from your new branch to the main branch
* 07:26 Switch which branch is serving the site

## Helpful demonstrations

There are many ways this could be completed. Here are a couple layout options if you're looking for suggestions.

* CSS grid layout: https://www.youtube.com/watch?v=qTGbWfEEnKI
* Another CSS grid layout: https://www.youtube.com/watch?v=v5KzBPUEgGQ

I found the gaps between the boxes was easy to get using grid-gap. In the videos the presenters used the body tag as their containters. The CSS would look like:

```Css
body {
  margin: 0;
  display: grid;
  grid-gap: 2vh;
 }
 ```
