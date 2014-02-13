---
layout: post
title: "Outline for building Rails app with basic CRUD interface"
date: 2014-02-12 21:04:16 -0500
comments: true
published: false
categories: [Rails, TDD, notes]
---

This post is meant to be a basic outline for the steps to take when creating a
Rails app with a basic CRUD interface. There will be no specific code listed.
There are plenty of books and tutorials that explain the code needed in detail. 

These steps were compiled while reading through ["Rails 4 in
Action"](http://www.manning.com/bigg2/). It is assumed that the app will be
built using TDD, favoring RSpec. 
<!-- more -->

## New app ##

* Start by creating a new rails app
* Install gems
* Install binstubs
* Configure database if necessary

## Create ##

* Create any spec directories required i.e., `spec/features` if using RSpec
* Write first test/spec for creating your resource
    * Navigate to page where form is located
    * Fill in necessary info
    * Click button to create the resource
    * List assertions
* Run tests/specs to make sure you get a failing test
