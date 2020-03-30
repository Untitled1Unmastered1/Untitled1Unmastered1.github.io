---
layout: post
title:      "Portfolio Project 2: Building a CRUD, MVC App Using Sinatra: MuirLog "
date:       2020-03-30 07:13:30 +0000
permalink:  portfolio_project_2_building_a_crud_mvc_app_using_sinatra_muirlog
---


What a blast! It was a heck of a journey creating my first web app. I went ahead and created an app targeted at nature enthusiasts/ hikers named after the legendary "Father of the National Parks", John Muir. I opted out of using the Corneal gem, and was able to properly structure the MVC as well as every other file and folder required. 



HOW IT WORKS: Essentially, a user can create an account, upon doing so they are redirected to a feed displaying their own encounters at the very top , as well as other users' encounters. The User can either decide to create a log, view their profile which contains links to their own encounters, upon clicking on a link they can view the specific encounter of theirs, delete it, or edit it.  Or they can just stay on the index page and view other users encounters.  


WHAT DETAILS CAN THEY LOG INTO THEIR ENCOUNTERS?  The user must fill all fields required, I set up conditionals to verify that user input is not missing any required fields(as well as to verify that user credentials have been input correctly). They must set a date, the name of the animal, the general location, the coordinates or area of said general location, as well as a description of the lovely encounter. 


I really enjoyed the beauty of metaprogramming thanks to ActiveRecord.  I was a bit worried during the SQL bits of the curriculum, especially memorization of queries, but AR came through! Lots of time saved. The BCrypt gem was also one of my favorite bits, despite not working directly with it, knowing what's going on behind the scenes was pretty mind-blowing. Sessions and Cookies I had some prior knowledge of but the curriculum really fleshed that out. I wish I hadn't skipped out on the bonus lessons for CSS and HTML, but it is my current goal to improve upon it. A lot of googling was involved for that bit. I also wasn't able to enjoy the Flash gem, due to an "uninitialized constant error" I received upon bundling it then registering it on the main app controller. 

Regardless, it was an amazing experience and I hope everyone enjoys it. I'm very satisfied with the final product. Can't wait to jump into Rails! 




