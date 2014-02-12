---
layout: post
title: "Rubygems certificate verify failed"
date: 2014-02-11 23:22:14 -0500
comments: true
categories: 
---

When trying to bundle install on one of my Rails apps, I got an error saying
that 'certificate verify failed'. I believe the rvm certificates were out of
date. What I found to work was `rvm rubygems latest`. After that I did my 
`bin/bundle` and everything worked perfectly.
