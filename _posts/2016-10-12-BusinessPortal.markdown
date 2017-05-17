---
layout: post
title:  "Syracuse Business Portal"
category: CodeforAmerica
thumbnail: "/images/thumbs/small-biz.png"
description: "Education, resources, and permit tracking for entrepreneurs."
faketag: UX/UI design, Visual design
---

![Business Portal homepage](/images/smallbiz-syr-homepage.png)


How can the city of Syracuse, New York best serve local business owners? With a small, but dedicated staff, the city's Division of Business Development needed an online presence to complement their in-person services.

>"To grow our economy we don't have the ability to talk to every single person with an idea. We felt it was important to make that if you have an idea, you have a place to go to start thinking about it.” - [Deputy Commissioner of Business Development](http://wrvo.org/post/syracuse-web-portal-one-stop-shop-businesses)

We built [business.syrgov.net](https://business.syrgov.net/), a portal where local entrepreneurs can learn about starting a business, find city regulations, check the status of their permits, and more. 

I was the product designer on this team, were I worked alongside a service designer, a product manager, and several engineers.


# Process


![Variations on search prompt text.](/images/smallbiz-tracker-iterations.png)
<small>Microcopy iterations. Every detail of the site was designed with care, and I went through multiple iterations of each aspect of the site.</small>

## Accessibility 
A government website must serve all residents. I needed to meet users where they were, which includes a diverse range of abilities, devices, languages, and levels of digital literacy. I designed the layout mobile-first, so users would have an excellent experience whether they were on their phone or a desktop computer. I chose system fonts so the content would load quickly, even for users on poor connections. 

## Visual Design 
The visual identity is designed to be to modern and approachable, yet authoritative. Entrepreneurs should feel welcome on the site, and trust it to give them accurate, up to date information on regulations and requirements.

## Hierarchy and Navigation

Our research uncovered that one of the biggest barriers facing new business owners is a lack of knowledge of the landscape. Specifically, they "don't know what they don't know". It was important to give users a clear path to navigate the site, whether or not they knew exactly what they were looking for.

![](/images/smallbiz-syr-layout-iterations.png)
<small>Wireframes iterating on the homepage layout.</small>

 We built on Code for America's [2016 Fellowship in Long Beach](https://www.codeforamerica.org/government-partners/long-beach-ca), where they piloted the Plan, Open, Grow model. To this I added several forms of navigation, including bread crumbs and a table of contents for each section. This allows experienced users to jump to the exact topic they're interested in, while also providing a clear path to new users.

## Human Touch
![Screenshot of an interior page](/images/smallbiz-syr-content.png)
<small>Screenshot of an interior page.</small>

Our research showed that that users highly value the ability to interact directly with city staff. I broke up long blocks of content with easily clickable contact links.  


# Application Tracker

Previously, business owners needed to call the city to find out the status of their business license and  permit applications. Our application tracker pulls in data from the city's permitting software, giving applicants access to quick, up to date statuses. 

![Screenshot of different screens in the application tracker](/images/smallbiz-tracker-mockups.png)

My challenge was to present data so that users could easily find the information that was relevant to them. For logistical reason, we needed to let users look up applications with tracking number, without logging into an account. The applications contain many steps and sub-steps. A developer looking for information on why an inspection failed has different needs than a business owner who wants to know when their license expires.

I broke the data up into logical sections with clear headings and added icons and colors to help users scan and understand the information at a glance. I designed a summary section at the top with the overall application status and time sensitive information. For one step of the application, we were unable to get live data from the city's permitting system. To help users understand what was happening in this step, I added a plain language explanation of the process. This compromise keeps users from feeling in dark as they wait for the outcome.