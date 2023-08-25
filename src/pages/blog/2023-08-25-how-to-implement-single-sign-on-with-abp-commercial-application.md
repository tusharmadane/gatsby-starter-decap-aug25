---
templateKey: blog-post
title: How to implement Single Sign-On with ABP commercial application
date: 2023-08-25T08:42:13.772Z
description: There are lots of reasons for using SSO for custom applications
  owned by the same enterprise organization. SSO establishes better user
  experience, less development time and improved security.
featuredpost: true
featuredimage: /img/implement-single-sign-on-with-abp-commercial-1-.png
---
#### Introduction

There are lots of reasons for using SSO for custom applications owned by the same enterprise organization. SSO establishes better user experience, less development time and improved security. SSO also enables to upgrade a large codebase a piece at a time instead of all at once, you will be able to effectively link them together as if they were one. In this article, we’ll simulate such a scenario by implementing SSO for an .Net core MVC application and an ABP Commercial modular application. Through this article you will also learn how the two platforms implement authentication.

```html

    @{ 
       ViewData["Title"] = "Home Page";
       
    }

    <div className="text-center">
    <h3 className="display-6">
        Welcome to Authentication Module
    <h3>       
    <h2> 
        <a  href="http://localhost:4200/dashboard" target="_blank">
        Login ABP</a>    
    </h2>   
    </div>
```