[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fhugginsio%2Fgo&project-name=url-shortener&repository-name=vercel-url-shortener)

A simple, straightforward URL shortener, powered by [Vercel Redirects](https://vercel.com/docs/projects/project-configuration#redirects). Take a look at [vercel.json](./vercel.json) to see how it works.

Customization is simple. Adding a new redirect is as simple as inserting a new definition at the top of the `redirects` array. Your redirect can be a simple static URL or a dynamic URL that uses pattern matching to very intentionally redirect end users.

Here, try a few:

- [url-shortener-with-redirects.vercel.app/docs](https://url-shortener-with-redirects.vercel.app/docs)
- [url-shortener-with-redirects.vercel.app/github/hugginsio](https://url-shortener-with-redirects.vercel.app/github/hugginsio)
- [url-shortener-with-redirects.vercel.app/](https://url-shortener-with-redirects.vercel.app/)

A tip: leave a root wildcard redirect (`/(.*)`) at the end of the array so that users who navigate to removed or incorrect short URLs are redirected somewhere useful, like your website.
