# mvcBasics

Model - Data

View - HTML/CSS

Controller - Management

import packages either through SDKs or nuget packages which is like npm
where the package is located is where you know what type of package it is

sdk packages are added by manually selecting them (add reference)

right click Manage Nuget package

data usually gets stored on an extenal server or sql server

App data - if your using sqlite might go in here not used as much

App Start - a few special files that configure how the application is handled and what it does when it starts up

Content - static content (usually put images) and standard css files

Scripts - includes all js files

Web.config - information or configuration items these settings might be changed often (database strings and contact email addresses and details)

.cshtml use @ a lot - razor syntax 
can grab values from your controller and present it in the views

views in mvc:
 - razor is just the engine that mvc uses to process our c# code to generat the dynamic page html
 
 - .cshtml is an extenstion that helps the mvc runtime indentify pages that should have dynamic content
 - when linking you don't lint to About.cshtml you just link to About
