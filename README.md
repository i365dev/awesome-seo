# awesome-seo

[简体中文](./README_CN.md)

A carefully curated collection of SEO guides, tools, and references for people who build and operate websites. Started as personal SEO notes in 2019; now maintained as a public knowledge resource by [i365](https://www.i365.tech/).

**New to SEO?** Begin with [Google Search Essentials](https://developers.google.com/search/docs/essentials) and the [official SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide). Use Search Console to measure search visibility before choosing tools.

**Curation policy:** This is a reference list, not a product directory, advertising channel, or backlink placement service. Unsolicited vendor and self-promotional listings are not accepted. See [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## Basic Concept

### The SEO improvement loop

```mermaid
flowchart TD
    intent["Search intent and user needs"] --> content["Useful, distinctive content"]
    content --> access["Crawlable and indexable pages"]
    access --> visibility["Potential search visibility and visits"]
    visibility --> evidence["Measure with Search Console and site analytics"]
    evidence --> improve["Fix issues and improve content"]
    improve --> content
```

*Indexable does not mean ranked: visibility depends on relevance, competition, and search-engine decisions.* The loop is about publishing helpful pages, observing results, and improving them—not producing links or content for their own sake.

The following older mind map is a broad reference; check current [Google Search documentation](https://developers.google.com/search/docs) for technical guidance.

![What is SEO](https://img.bmpi.dev/4351f5c8-cc00-d2a8-a75f-9010c9367893.png)

## Tutorials

[Google Search Essentials](https://developers.google.com/search/docs/essentials)
> Google's baseline technical requirements, spam policies, and search best practices.

[Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)
> Google's introduction to making content accessible, useful, and discoverable through Search.

[The Beginner's Guide to SEO](https://moz.com/beginners-guide-to-seo)
> SEO beginners tutorial on the Moz web, helps you learn SEO systematically.

[The Authority Site System 3.0](https://www.authorityhacker.com/system/)
> This course is about how to build an authority site ( Niche Site) from scratch and make money from it. SEO is only a part of it, it also includes Affiliates, Paid-advertising etc. (The course is pretty expensive, and I haven't started it yet)

[A Technical SEO’s Guide to Crawl Budget Optimization](https://prerender.io/resources/free-downloads/white-papers/crawl-budget-guide/)
> A comprehensive guide explaining the importance of crawl budgets in managing indexing for search engines, how it impacts website traffic, and provides optimization tips to improve online visibility and SEO results.


## Books

[The Art of SEO](https://book.douban.com/subject/3780812/)
> In this book, four of the most noted experts in the field of search engine optimization (SEO) provide you with proven guidelines and cutting-edge techniques. The third edition was written in 2015, so if you only want to read one book about SEO, this book is the best option.

[这就是搜索引擎](https://book.douban.com/subject/7006719/)(Chinese Book)
> This book is about the internal technology of popular science search engines. Although Using SEO does not need to understand the internal implementation of search engines, for some technical optimization, understanding the characteristics of some search engines will help you optimize your website from a macro perspective.

## Article/Video

[How Search Works](https://www.youtube.com/watch?v=BNHR6IQJGZs)
> The videos about popular science search engine that Google published.

[12 SEO Best Practices That Everyone Should Follow](https://ahrefs.com/blog/seo-best-practices/)
> SEO best practices that Ahrefs write.

[17 Actionable Content Marketing Tips For More Traffic](https://backlinko.com/content-marketing-tips)
> The content marketing is one of important directions in SEO. The article content mainly involves content marketing suggestions, and it written by Brian Dean who research backlink.

[Here’s What We Learned About SEO](https://backlinko.com/search-engine-ranking)
> The article studies the factors influencing search engine rankings through large amounts of data analysis.

[What Is SEO Writing? How to Be a Better SEO Writer](https://ahrefs.com/blog/seo-writing/)
> The article mainly introduce the writing framework of SEO, and suggestions about how to be a better SEO write.

[The Authority Site Business Model](https://www.authorityhacker.com/what-is-an-authority-site/)
> The article introduce the whole process that an authority site from construction to profitability.

[零成本搭建SEO友好型博客指南](https://www.bmpi.dev/series/%E9%9B%B6%E6%88%90%E6%9C%AC%E6%90%AD%E5%BB%BA%E7%8E%B0%E4%BB%A3%E5%8D%9A%E5%AE%A2%E6%8C%87%E5%8D%97/)(Chinese Blogs)

> This is a series of blogs that introduces how to build a SEO from scratch. These blogs content covered blog building, SEO optimization, subcribe and push, website loading speed optimization.

[Logfile Analysis for SEO](https://www.suganthan.com/blog/logfile-analysis-seo/)
> This article detail explains how to analyse website access logs to identify problems in SEO. Google Analytics can help us understand user access, and system logs can help us better understand crawler requests, website techical SEO issues such as 301 redirects and so on.

### Google Ads

[Google Ads Benchmarks for YOUR Industry](https://www.wordstream.com/blog/ws/2016/02/29/google-adwords-industry-benchmarks)
> Last updated: October 5, 2020. 
> It can help to learn about the money-sucking power of each industry.

[如何准确查询关键词热度和搜索量](https://www.onepound.cn/article_info-144.html)(Chinese Website)

> For knowing what's hot on the web and avoiding Red Sea competition.

## Tools

The resources below prioritize official search-engine tools, mature open-source projects, and established industry tools—not new vendor listings.

### Search performance and indexing

[Google Search Console](https://search.google.com/search-console/about)
> Google's first-party tool for search queries, page performance, indexing, and crawl diagnostics.

[Search Console API](https://developers.google.com/webmaster-tools/)
> Query Google Search data, manage sitemaps, and inspect URL indexing status programmatically; requires property access.

[Bing Webmaster Tools](https://www.bing.com/webmasters/about)
> Microsoft's first-party search performance, indexing, crawling, and keyword diagnostics.

[Google Trends](https://trends.google.com/trends/explore)
> Compare relative search interest and trends across topics, regions, and time; not a source of absolute search volume.

### Technical auditing and structured data

[Google Rich Results Test](https://search.google.com/test/rich-results)
> Google's official test for structured data eligible for rich-result features in Google Search.

[Schema Markup Validator](https://validator.schema.org/)
> Validate Schema.org JSON-LD, RDFa, and Microdata independently of Google-specific rich-result eligibility.

[Google Lighthouse](https://github.com/GoogleChrome/lighthouse)
> Google's open-source audits for page performance, accessibility, SEO, and best practices.

[Lighthouse CI](https://github.com/GoogleChrome/lighthouse-ci)
> Run Lighthouse audits and regression assertions in continuous integration.

[Screaming Frog SEO Spider](https://www.screamingfrog.co.uk/seo-spider/)
> Established desktop crawler for technical SEO, including broken links, redirects, and metadata; the free version crawls up to 500 URLs per run.

### Other established tools

[advertools](https://github.com/eliasdabbas/advertools)
> Python library providing a comprehensive set of SEO and digital marketing tools.

[ahrefs](https://ahrefs.com/)
> SEO conprehensive analysis tool. 

[semrush](https://www.semrush.com/)
> SEO conprehensive analysis tool. 

[Screpy](https://screpy.com/)
> SEO platform for technical audits, rank tracking, Core Web Vitals, uptime monitoring, and reports.

[webpagetest](https://www.webpagetest.org/)
> Website speed measurement tool, essential for technical SEO optimization.

[google pagespeed insights](https://developers.google.com/speed/pagespeed/insights/)
> Website speed measurement tool, essential for technical SEO optimization.

[majestic](https://majestic.com/)
> Website Backlink Analysis Plugins. 

[moz](https://moz.com/)
> Open Site Explorer/MozBar Plugins. 

[linkresearchtools](https://smart.linkresearchtools.com/seo-tools/free-seo-tools/)
> Free SEO Tools. 

[raventools](https://raventools.com/)
> A comprehensive toolbox for link building. 

[authoritylabs](https://www.authoritylabs.com/)
> Track search engine rankings / Solve the problem of GA that keywords not provided.

[quantcast](https://www.quantcast.com/)

> Website Traffic View Tools. 

[seoquake](https://www.seoquake.com/index.html)
> SEO Chrome Plugin that published by semrush. 

[spyfu](https://www.spyfu.com/)

[Prerender](https://prerender.io/)
> Prerender serves 100% cached versions of your web pages to search engine bots that have problems executing JavaScript.

## Chrome Plugins

[SimilarWeb](https://chrome.google.com/webstore/detail/similarweb-traffic-rank-w/hoklmmgfnpapgjgcpechhaamimifchmp)
> The plugin to check the PV traffic of website. But the results are sometimes accurate and sometimes biased.

[SEOquake](https://chrome.google.com/webstore/detail/seoquake/akdgnmcogleenhbclghghlkkdndkjdjc)
> Check the SEO-related information of the website, such as the number of external links, the number of indexes, and SEO Internal website issues, etc.

[Keyword Surfer](https://chrome.google.com/webstore/detail/keyword-surfer/bafijghppfhdpldihckdcadbcobikaca)
> This is a keyword tool to view monthly search volume for a number of keywords. 
> Of course, you also can use Keyword Planner of Google Ads to view monthly search volume for a number of keywords. 

[SEO Minion](https://chrome.google.com/webstore/detail/seo-minion/giihipjfimkajhlcilipnjeohabimjhi)
> The view tool for common internal issues of website.

[META SEO inspector](https://chrome.google.com/webstore/detail/meta-seo-inspector/ibkclpciafdglkjkcibmohobjkcfkaef)
> The view tool for meta data of website.

## Blog/Twitter

[SEO Twitter List](https://twitter.com/i/lists/1341048200677842950)
> The list mainly show SEO masters Twitter.

[backlinko](https://backlinko.com/)
> Brian Dean’s Blog (He has some achievements in backlink research.)

[Google Search Central Blog](https://developers.google.com/search/blog)
> Published by Google.

[ahrefs blog](https://ahrefs.com/blog/)
> High-quality blogs about SEO that published by ahrefs. 

[moz](https://moz.com/blog)
> High-quality blogs about SEO that published by moz. 

[英文SEO实战派](https://www.seoactionblog.com/)(Chinese Blog)
> Author: John. He has amount of research on Google Authority Site.

[富裕者联盟](https://www.fuyuzhe.com/)(Chinese Blog)
> The author is Affiliate master, It can help you learn some online earning techniques.

[Harris](https://www.yesharris.com/learning-seo-menu/)(Chinese Blog)
> About SEO Timeliness.

[SEO前线](http://seoqx.com/)(Chinese Blog)
> Author: noname. He main research Baidu SEO.

[Other](https://ahrefs.com/blog/seo-blogs/)
> Collected by ahrefs.

## Community

[Reddit SEO](https://www.reddit.com/r/SEO/hot/)

[Black Hat World](https://www.blackhatworld.com/)

[Webmaster World](https://www.webmasterworld.com/home.htm)

[Warrior Forum](https://www.warriorforum.com/)

> If you want to recommend other good communities, please commit PR.

## Traffic Monetization

Organic search traffic creates opportunities, not revenue by itself. Common models include advertising, affiliate commissions, and selling products or memberships.

```mermaid
flowchart TB
    pv["Organic page views"] --> ads["Display advertising"]
    pv --> affiliate["Affiliate commissions"]
    pv --> products["Products and memberships"]
    ads --> revenue["Total revenue"]
    affiliate --> revenue
    products --> revenue
    revenue --> rpm["Blended RPM"]
    pv --> rpm
```

**Blended RPM = total revenue ÷ page views × 1,000.** This measures revenue per 1,000 page views across the channels shown; it is different from an ad platform's *ad-only* RPM. Track conversions and operating costs separately to understand profitability. Results vary by niche, geography, audience, and product fit—historical CPM/CPC benchmarks are not universal assumptions.

## Other

[Google Algorithm Update History](https://moz.com/google-algorithm-change)
> Currently, Google has some of more important Google algorithms including the Panda algorithm, the Penguin algorithm, and the Hummingbird algorithm.
> This is the page that Moz tracks updates to Google's search algorithm.

[State of the Web](https://httparchive.org/reports/state-of-the-web)
> Some reports on important statistics related to HTTP on the Internet, published by httparchive.

---

## Maintainers

Maintained by [i365](https://www.i365.tech/), an agent-native digital product studio. This list is an independent reference collection; inclusion does not imply endorsement, partnership, or payment.
