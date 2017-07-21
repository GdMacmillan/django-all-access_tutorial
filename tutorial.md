# The Missing Django-all-access Tutorial

Gordon MacMillan last edited this page on July 21, 2017 - 0 edits


This post is for people who are looking for a [django-all-access](https://github.com/mlavin/django-all-access) tutorial if, for whatever reason, [allauth](https://github.com/pennersr/django-allauth) is not able to meet your needs as an 3rd party app for authentication backend, registration and account management.

Recently I started building authentication into my application. I looked around and couldn't come up with a good tutorial on how to use django-all-access. I found several for allauth including a great [post by Sarah Hagstrom](http://www.sarahhagstrom.com/2013/09/the-missing-django-allauth-tutorial/), which served as the impetus for a post of my own.

I had already started building up my application with django-all-access, which is why I decided to stick with this package instead of switching to allauth. Still, I needed a testbed and since I had completed the [excellent tutorial](https://docs.djangoproject.com/en/1.11/intro/tutorial01/) from the Django docs, I figured that would be perfect.

I'm assuming you are using python 3.6 and Django 1.11 for this tutorial. Make

****Need to state dependencies***

## Part 1 - Writing the App
