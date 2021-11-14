---
title: "Example and teach"
date: 2020-02-10T13:24:17-07:00
draft: false
weight: 1
--- 
<link rel="stylesheet" href="../../style.css">

![image](../../img/queueIntro.png)

<h1>Visualizing a Queue</h1>

<hr>

Imagine that you are designing NuevoEats for a business, and perhaps this business is Chik-Fil-A.

We want to serve our new potential clients in the most efficient way possible for our large business; one at a time. When customers place their togo order on the NuevoEats app, it is almost as if they are forming an orderly line in front of our restaurant, with new customers joining at the rear. Customers should essentially "line up" when they place their order and we should be serving those same customers from front to back.

Queues in Java work in a similar way. After we declare our Queue, we can add new elements to the back, and remove them from the front.

In fact, most Queues we'll encounter in Java work in this first in, first out manner – often abbreviated to FIFO.