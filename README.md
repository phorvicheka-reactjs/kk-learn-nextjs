# Learn Next.js
The React Framework
https://nextjs.org
https://github.com/zeit/next.js

It's no secret that creating single-page JavaScript applications can be pretty challenging these days. Fortunately, there are multiple frameworks and libraries to choose from.

Even still, there's a high learning curve before you can build a proper application. That's because you need to learn about client-side routing, page layout, APIs, and so on. Furthermore, you may want to server-side render certain pages and statically prerender others (balancing SEO and speed).

**So, we need something simple but customizable.**

Think about how webapps are created with PHP. You create some files, write PHP code, then simply deploy it. We don't have to worry about routing much, and the app is rendered on the server by default.

## Next.js
That's exactly what we do with [Next.js](https://github.com/zeit/next.js). Instead of PHP, we build the app with JavaScript and React. Here are some other cool features Next.js brings to the table:

* An intuitive page-based routing system (with support for dynamic routes) Automatically statically optimizes page(s) when possible
* Server-side renders page(s) with blocking data requirements 
* Automatic code splitting for faster page loads
* Client-side routing with optimized page prefetching
* Webpack-based dev environment which supports [Hot Module Replacement](https://webpack.js.org/concepts/hot-module-replacement/) (HMR)
* API routes to build your API with serverless functions, with the same simple router used for pages
* Customizable with community plugins and with your own Babel and Webpack configurations Sounds great, right? Let's give it a try.