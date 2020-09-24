---
title: assemblr
summary: An R package and addin whose aim is to make it easier to build regression tables
abstract: ""
date: "2020-09-24"
image:
  caption: ""
  focal_point: ""
  preview_only: true
categories:
- R
tags:
- R
---

`{assemblr}` is an R package and addin whose aim is to make it easier to build regression tables. More specifically, it provides an interactive environment to create regression tables with the `{stargazer}` package. You can check the development of this package [here](https://github.com/etiennebacher/assemblr).

**Why `{assemblr}`?**

During my academic works with `R`, I used a lot the `{stargazer}` and `{texreg}` packages to produce regression tables. These are incredibly helpful, and provide a lot of options to customize the LaTeX format, which I primarily use. However, it is easy to be lost among all of these options, and it's not really possible to know exactly what the table will look like.

Therefore, I thought it would be a good idea to create an RStudio addin that takes the form of a Shiny app, and that allows to design regression tables with live preview. With this, the users could actually play with the multiple options, and easily check if they like them or not. All of these options would then be saved and the code to build the corresponding table would be provided when the user is done.

Besides being useful for the user, this project is also useful to me! Indeed, it has become the way to learn how to make an R package, how to make an RStudio addin (which is not hard once you have a package), and how to use the `{golem}` package for Shiny apps. 
