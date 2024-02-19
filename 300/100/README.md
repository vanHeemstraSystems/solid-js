# 100 - What is Solid Start?

**WARNING**: We are very excited about SolidStart, but it is currently in beta. There will very likely be **bugs and missing documentation**. Come at it with a growth attitude, have fun, and don't use it yet for anything critical. If all this darkness doesn't faze you, press onward, and consider joining the [Discord](https://discord.com/invite/solidjs) to ask questions. We would love to meet you. 

Web applications often comprise many components: databases, servers, front-ends, bundlers, data fetching/mutations, caching, and infrastructure. Orchestrating these components is challenging and often requires a large amount of shared state and redundant logic across the application stack.

Enter SolidStart: a meta-framework that provides the platform to put all of these pieces together in a one location.

Start is considered a *meta-framework *(a framework built on top of another framework) because, at its core, Start is powered by [SolidJS](https://solidjs.com/). It uses [Vinxi](https://vinxi.vercel.app/) an agnostic Framework Bundler combining the power of [Vite](https://vitejs.dev/) and [Nitro](https://nitro.unjs.io/).

Unlike other Metaframeworks SolidStart does not aim to be too opinionated. It provides the minimal amount of pieces to get you up and going. While there are templates that include many of the expected tools, SolidStart itself does not ship with a Router or Metadata library. Instead it leaves it open to using which ever libraries you feel comfortable with.

SolidStart enables you to render your application in different ways depending on what's best for your use case:

- Client-side rendering (CSR)
- Server-side rendering (SSR)
- Streaming SSR
- Static site generation (SSG)

If you're not familiar with these, that's okay! As we progress through these docs, we'll talk a bit about different ways to render your applications and help you choose the best fit.

One of the driving principles of SolidStart is that code should be *isomorphic* — you should be able to write code once, and it will run correctly regardless of whether it's being run on the client or server. As we move through the docs, we'll discover just how powerful isomorphism is!

## 100 - Features

See [README.md](./100/README.md)

## 200 - Prerequisites

See [README.md](./200/README.md)

## 300 - SolidStart is in Beta!

See [README.md](./300/README.md)
