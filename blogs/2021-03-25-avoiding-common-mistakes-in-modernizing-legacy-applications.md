---
title: "Avoiding common mistakes in modernizing legacy applications"
url: "https://www.redhat.com/en/blog/avoiding-common-mistakes-modernizing-legacy-applications"
date: "2021-03-25"
feed_url: "https://www.redhat.com/en/rss/blog/channel/red-hat-middleware"
---
The Problem Recently, I worked with a customer in the courier industry whose core logistics scheduling application suffered from reliability, performance, and scalability issues. While I addressed the immediate problems, it was clear that the 20 years of patchwork fixes, enhancements, and technical debt accumulated were the root cause. The legacy architecture consisted of four Red Hat JBoss Enterprise Application Platform servers, each with an instance of the logistics scheduling application deployed and an embedded Artemis broker to handle the messaging.
