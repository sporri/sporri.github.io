---
layout: post
title: Það segir sig sjálft
date: 2009-01-10 00:06
author: sporri
comments: true

---
a boundary value of ‘2008-08-30T23:59:59.999’ for a datetime partition function will get rounded up to ‘2008-08-31T00:00:00.000’ and result in data for midnight (‘2008-08-31T00:00:00’) getting inserted into the left partition instead of the right.
