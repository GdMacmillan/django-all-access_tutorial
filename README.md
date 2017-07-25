
# The Missing Django-all-access Tutorial

This is an app using [django-all-access](https://github.com/mlavin/django-all-access)  which provides an environment to test and learn from.

Recently I started building authentication into my application(recklessly). I looked around and couldn't come up with a good tutorial on how to use django-all-access. I found several for allauth including a great [post by Sarah Hagstrom](http://www.sarahhagstrom.com/2013/09/the-missing-django-allauth-tutorial/), which served as the impetus for a post of my own.

I had already started building up my application with django-all-access, which is why I decided to stick with this package instead of switching to allauth. Still, I needed a testbed and since I had completed the [excellent tutorial](https://docs.djangoproject.com/en/1.11/intro/tutorial01/) from the Django docs, I figured that would be perfect.

I'm using python 3.6 and Django 1.11 for this app

## Part 1 - Writing the App

In order to make this as explicit as possible, I'll go ahead and run through the tutorial quickly. I'm not going to explain everything about this code. That is what the docs are for. Keep in mind the original tutorial has just a polls app that runs at localhost:8000/polls. For mysite, I went ahead and added a homepage view that can be accessed from locahost:8000 and links to the polls app.

## Part 2 - Adding Authentication

Django all-access is a helpful third party if you want to build some easily customizable and robust authentication measures into your web or mobile app. I am by no means an expert in this space but I regarded the tutorial and documentation as accessible enough to integrate. It abstracts away several base Oauth classes and is built on the handy requests library so it integrates well with other third party applications built around administration and authentication with Django.

My tutorial uses Strava's API as an example. Handshake is done using the OAuth 2.0 protocol. My application is registered on their site but for all intents and purposes, I will not be sharing the details of that registration.

To install django-all-access, run `pip install django-all-access`. One point to note: if you haven't been using a virtual environment up until this point, now is a good time to learn. I am using a [anaconda](https://conda.io/docs/using/envs.html) to manage my python 3 environment.
