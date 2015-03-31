---
layout: post
title: "How to Deploy your Jekyll Site"
---

# Buy a Doman
I have bought domain names through several companies.  I haven't used [GoDaddy](https://www.godaddy.com) for several years, but they used to be notorious for a confusing checkout process in which they were notorious for upselling products.  In contrast, [Hover](https://www.hover.com) proviides a smooth and uncluttered way to search for a domain and to purchase it.  I highly recommend Hover.  

# Configure the DNS

Refer to the [Netlify documentation](https://docs.netlify.com/custom_domains/), but here is the relavent snippet:

	* Create a CNAME that will "alias" your site to www.netlify.com. If your domain is example.com, you might alias www.example.com to www.netlify.com.
	* Create an A record for the raw domain (example.com) pointing to 198.61.251.14

	

