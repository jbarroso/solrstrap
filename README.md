#Solrstrap

[Solrstrap](http://fergiemcdowall.github.com/solrstrap/) is a Query-Result interface for Solr. [Solrstrap](http://fergiemcdowall.github.com/solrstrap/) is intended to be a starting point for those building web interfaces that talk to Solr, or a very lightweight admin tool for querying Solr in a Googleish fashion.

[Download the latest release of Solrstrap here](https://github.com/fergiemcdowall/solrstrap/zipball/master) or visit https://github.com/fergiemcdowall/solrstrap/ for other download options

The Solrstrap homepage is at http://fergiemcdowall.github.com/solrstrap/

#What does Solrstrap do?
Solrstrap takes search queries and displays search results. It also features:
* Instant search
* Restful interface (you can link directly to /solrstrap.html?q=doughnuts)
* Functioning history

#Solrstrap is probably the fastest available rendering engine for Solr.

This is because it does everything in Javascript, CSS and HTML on the client side. JSON is shot back from the server and interpeted by the web browser.

Solrstrap therefore requires much less server power and bandwidth than standard search-middleware applications.

#Installation, How do I make it work?
Optionally edit SERVERROOT in /js/solrstrap.js to point to the "select" endpoint of your solr instance, and HITTILE/HITBODY to reference the appropriate fields in your index

Click on /solrstrap.html.

Thats it.

#What is Solrstrap made of?
Solrstrap is lovingly crafted from [Bootstrap](http://twitter.github.com/bootstrap/) and [Handlebars](http://handlebarsjs.com).

#Strengths
* Requires _only_ local installation- very easy to set up
* Access to all Bootstrap functionality. Can be easily extended in a Bootstrappy way.
* Blazing fast
* Uses very little bandwidth

#Weaknesses
* Designed for "open" solr instances- needs clear access to /select/q=.
* SEO basically non-existant
* Will (probably) not work on truly ancient browsers (IE 7 and below)

#Future releases
* Support for facets...
* Support for infinite scrolling...
* Some form of arrow key functionality...

#License
Issued under the Gnu Public License v3 as per /gpl-3.0.txt

#Get Solrstrap
Follow the download links or cloning instructions on https://github.com/fergiemcdowall/solrstrap/

#Contact
Follow/contact me on Twitter [@fergiemcdowall](https://twitter.com/fergiemcdowall)

I write articles about search engine technology here: http://blog.comperiosearch.com/blog/author/fmcdowall/