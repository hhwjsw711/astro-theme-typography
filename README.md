# Typography

This work astro-theme-Typography is rewrite from [hexo-theme-Typography](https://github.com/sumimakito/hexo-theme-typography).

## Live Demo
https://blog.moeyua.com/
https://astro-theme-typography.vercel.app/

## Deploy

You can instantly clone this to your GitHub and deploy the site by clicking the below buttons to deploy to your chosen providers!

### Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmoeyua%2Fastro-theme-typography)

### Deploy to Netlify
  
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Fmoeyua%2Fastro-theme-typography)


## Features
- [x] archive
- [x] category
- [x] pagination
- [x] config file
- [x] responsive
- [x] seo
- [x] rss
- [x] i18n
- [x] robots.txt
- [x] sitemap
- [ ] WebSub
- [ ] dark mode

## Config
You can config the theme in [src/theme.config.ts](src/theme.config.ts)

```ts
export const THEME_CONFIG: App.Locals['config'] = {
  /** your blog title */
  title: "Typography",
  /** your name */
  author: "Moeyua",
  /** website description */
  desc: "A minimal, responsive and SEO-friendly Astro blog theme.",
  /** your deployed domain, you should also change the site in astro.config.ts */
  website: "https://astro-theme-typography.vercel.app/",
  /** your locale */
  locale: "en-us",
  /** your socials */
  socials: [
    {
      name: "github",
      href: "https://github.com/moeyua/astro-theme-typography",
    },
    {
      name: "rss",
      href: "/atom.xml",
    }
  ],
  /** your navigation links */
  navs: [
    {
      name: "Posts",
      href: "/posts/page/1",
    },
    {
      name: "Archive",
      href: "/archive",
    },
    {
      name: "Categories",
      href: "/categories"
    },
    {
      name: "About",
      href: "/about",
    },
  ]
}

```

## i18n
You can add language in [src/i18n](src/i18n.ts)

```ts
export const LANGUAGES = {
  'en-us': {
    Home: 'Home',
    Posts: 'Posts',
    Categories: 'Categories',
    ...,
  },
  'zh-cn': {
    Home: '首页',
    Posts: '文章',
    Categories: '分类',
    ...,
  },
  ...,
}
```

## Update
You can update the theme by running the following command in your project root directory.

```bash
pnpm update-template
```

and then, fix the conflicts.


## Pagespeed Score

[![Pagespeed Score](https://github.com/moeyua/astro-theme-typography/assets/45156493/26b37fd9-122a-48e5-90e9-db274c5dcbf6)](https://pagespeed.web.dev/analysis/https-astro-theme-typography-vercel-app-home-1/1enpbpw1e3?form_factor=desktop)

[![Built with Astro](https://astro.badg.es/v2/built-with-astro/small.svg)](https://astro.build)
