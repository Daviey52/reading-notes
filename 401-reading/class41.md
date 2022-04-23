# Class 41

## Dynamin Routes and deploying your Next.js App

[Home](https://daviey52.github.io/reading-notes/)

If fallback is false, then any paths not returned by getStaticPaths will result in a 404 page.
If fallback is true, then the behavior of getStaticProps changes:
The paths returned from getStaticPaths will be rendered to HTML at build time.
The paths that have not been generated at build time will not result in a 404 page. Instead, Next.js will serve a “fallback” version of the page on the first request to such a path.
In the background, Next.js will statically generate the requested path. Subsequent requests to the same path will serve the generated page, just like other pages pre-rendered at build time.
If fallback is blocking, then new paths will be server-side rendered with getStaticProps and cached for future requests so it only happens once per path.
Next.js allows you to statically generate pages with paths that depend on external data. This enables dynamic URLs in Next.js.

Next.js has two forms of pre-rendering. They are Stactic Generation and serverside rendering. The difference appear when rendering the HTML for a page

1. Static Generation is the pre-rendering method that generates the HTML at build time. The pre-rendered HTML is then reused on each request
2. Server-side rendering is the pre-rendering method that generates the HTML on each request.
It is important to note that Next.js allows you to choose which pre-rendering form to use for each page. You can even create a ‘hydrid using both static generation and server-side rendering.’

Vercel is a serverless platform for static and hybrid applications built to integrate with your headless content, commerce, or database. We make it easy for frontend teams to develop, preview, and ship delightful user experiences, where performance is the default.

Vercel has many more features, such as:
Custom Domains: Once deployed on Vercel, you can assign a custom domain to your Next.js app. Take a look at our documentation here.
Environment Variables: You can also set environment variables on Vercel. Take a look at our documentation here. You can then use those environment variables in your Next.js app.
Automatic HTTPS: HTTPS is enabled by default (including custom domains) and doesn't require extra configuration. We auto-renew SSL certificates.
