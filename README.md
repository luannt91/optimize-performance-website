# Optimize Performance Website


## Front-end
* Make Fewer HTTP Requests
* Put Stylesheets at the Top 
* Put Scripts at the Bottom
* CSS Sprite
* Load Asynchronous Scripts file.
* Optimize Images: Compress, size specific, don’t scale

## Back-end
* Database
  * Indexes
  * Avoid (n+1) query: includes
  * Batch loading
  * Transaction 
  * Run big process in background jobs
  * Use DNS: To serve images, assets (Sharding Dominant Domains)
  * For Rails: Upgrade Rails, update gems, reduce gems
* Caching: 
  * Fragment caching
  * Query caching
  * Redis caching
* Avoid Redirects
  
## Server (Nginx)
* Add an Expires Header
* Gzip Components
* Using proxy to cache
* Config number of Worker on Web Server (Nginx)
* Using HTTP2

## Tools for monitor
* New Relic
* Pingdom

## Tools to measure Speed
* PageSpeed Insights: https://developers.google.com/speed/pagespeed/insights
* GTMetrix: https://gtmetrix.com
* Webpagetest: https://www.webpagetest.org

## Resources
* High Performance Web Sites Book
* PageSpeed Insights Rules: https://developers.google.com/speed/docs/insights/rules
* Best Practices for Speeding Up Your Web Site: https://developer.yahoo.com/performance/rules.html

