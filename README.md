# Improving Site Performance

## Description

Learn why site performance is important for all WordPress sites, and learn tips to improve it.

## Objectives

At the end of this lesson, you will be able to:

*   Recognize the factors that affect WordPress site performance.
*   List the ways you can improve WordPress site performance.

##  Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   [Installing and activating plugins](https://make.wordpress.org/training/handbook/user-lessons/choosing-and-installing-plugins/) on a self-hosted WordPress website.

## Screening Questions

*   Do you have a self-hosted WordPress.org website (vs. WordPress.com website)?
*   Have you installed plugins before?

## Teacher Notes

*   **Time Estimate:** 20 minutes
*   The preferred answers to the screening questions are “yes.” Participants who reply “no” to any question may not be ready for this lesson.
*   You may print out the hands-on walkthrough to use as a handout or send it as a .pdf file to stay green. A .pdf will also preserve the links used throughout the document.
*   It might make sense to have a discussion around the first part of the walkthrough, to assess site performance criteria & what improvement methods students are familiar with already.
*   It might be a good idea to follow this lesson with [What is W3 Total Cache](https://make.wordpress.org/training/handbook/lesson-plans/user-lessons/what-is-w3-total-cache/). This will help students to have a better understanding of the practical applications of the ideas listed in this lesson.

## Hands-on Walkthrough

### What is WordPress site performance?

WordPress site performance is characterized by how fast pages on a site load. There are several reasons why performance matters:

*   Better performance brings a better visitor/customer experience.
*   Google and other search engines rank sites based on performance; sites with better performance rank higher.
*   Adequate site response helps to decrease bounce rate, the rate at which users "bounce off" your site and go somewhere else.

There are some impressive statistics regarding website performance ([source](https://blog.kissmetrics.com/loading-time/)):

*   40% of people abandon a website that takes more than 3 seconds to load.
*   A one second delay in page response can result in a 7% reduction in conversions.
*   47% of consumers expect a web page to load in 2 seconds or less.

So it makes sense to invest some time to ensure your site is optimized and performs well.

### How to measure site performance

Now that you know why site performance is important, it's time to discuss how it’s measured and learn how to check your site's speed. This will give you a benchmark measurement before you start improving it.

The best way to measure site speed is to use a speed measurement service. [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights/) is among the most popular and is an excellent way to measure your WordPress site's performance on different devices. It will also help you to obtain specific feedback on what should be improved.

### What can impede performance?

When a website visitor's device requests data from a website hosted on a server, there are two primary bottlenecks that may slow down the data transfer:

*   Host - the kind of hosting you choose has a big impact on your site's speed. Shared hosting is managed by the hosting provider manages and you don't have much control. A hosting company with good reviews and decent prices is generally OK for beginners and non-critical websites. If you decide to have a dedicated server to host your site, pay attention to the number of servers and hardware used.

*   Network - sometimes the network your visitor uses to access your site is not ideal. And even if it's good, if your site has a lot of content, it will take time to process and load it. Most optimizations this lesson plan explores strive to reduce the amount of data transferred between a server and a visitor.

### How to optimize your website?

There are several popular ways to boost the performance of a website.

#### Caching

Caching stores some of the information that has already been requested, so it can be instantly served to the client when they request it again. This reduces the processing time when reloading a page repeatedly.

Caching also minimizes server load. Normally, when a visitor comes to your site, WordPress executes one or more (and often many) MySQL queries and PHP scripts to locate a requested page. Then the requested resources are parsed and PHP generates a page to display to the visitor, using server resources.

With page caching on, you can display a cached copy of the page as soon as it’s requested, without sending a request to the server.

There are plenty of caching plugins available, such as [W3 Total Cache](https://wordpress.org/plugins/w3-total-cache/), which allows browser, page, object and database caching. Some of the most popular alternatives are [W3 Super Cache](https://wordpress.org/plugins/wp-super-cache/), which has fewer options to customize so may feel less overwhelming, and [WP Rocket](http://wp-rocket.me/), which is an efficient but simple premium plugin.

#### Offloading

Another way to increase the speed of content delivery is to offload some of your content to other servers. A CDN can be used for this. CDN stands for _Content Delivery Network_.

A CDN is a network of servers, usually located at various sites around the world. These powerful servers can cache the static content of a site, such as image, CSS, and JavaScript files. When a visitor lands on your site, the content is provided by the server closest to their location. Popular CDN providers include [CloudFlare,](https://www.cloudflare.com/) [Amazon Cloudfront](http://aws.amazon.com/cloudfront/), [MaxCDN](http://www.maxcdn.com/), and [KeyCDN](https://www.keycdn.com/). You can also outsource hosting of your static content and RSS feeds.

#### Optimizing your site's configuration

The theme and plugins that you use on a site are very important for the site's performance. A fast, lightweight theme will perform much better than a heavy graphic-laden theme. If you have a lot of plugins activated, that can also affect performance. Make sure all the plugins you don't need are deactivated and deleted.

#### Compressing

You also can minify your content so that pages are quickly delivered to readers' browsers. For example, the [W3 Total Cache](https://wordpress.org/plugins/w3-total-cache/) plugin mentioned earlier includes a minify module which lets you control whether HTML, CSS, and Javascript files are minified and compressed. 

Minification removes all unnecessary or redundant data from the code without affecting performance, minimizing the size of the file that needs to be downloaded to the user's browser. This causes website pages to load faster and generally speeds up site operation. Plugins such as [WP Smushit](http://wordpress.org/plugins/wp-smushit/) or [EWWW Image Optimizer](https://wordpress.org/plugins/ewww-image-optimizer/) can help to compress images and other media files.

### Summary

Your site or blog's performance is very important for visitor experience and for its search engine ranking. The pillars for improving site speed are:

*   Choosing a reliable and powerful hosting provider
*   Enabling caching and compression
*   Making sure your site uses a lightweight theme and is not overloaded with plugins
*   Possibly using external services to offload part of your bandwidth

## Quiz

**Why is low performance bad for your site (choose as many as applicable)?**

1.  It shows content that you may not want your readers to see
2.  It distorts the visitor experience
3.  It could hurt your SEO
4.  It makes you pay more for the hosting of your website

**Answer:** 2. It distorts the visitor experience & 3. It could hurt your SEO

**Which of the following is a valid way for you to increase your site's performance?**

1.  Install and configure a caching plugin
2.  Schedule a backup strategy for your site
3.  Keep no active plugins at your site
4.  Make adjustments to site's Settings
5.  All of the above

**Answer:**  1. Install and configure a caching plugin

## Additional materials

Some more details on optimizing your website can be found at [WordPress Optimization/WordPress Performance](https://codex.wordpress.org/WordPress_Optimization/WordPress_Performance) section @ Codex
