Project Url : https://crypto-price-app-nine.vercel.app/


<br/>


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Installation

[Install Tailwind CSS with Next.js](https://tailwindcss.com/docs/guides/nextjs)

### Create your project

Start by creating a new Next.js project if you don’t have one set up already. The most common approach is to use [Create Next App](https://nextjs.org/docs/api-reference/create-next-app).



### Install Tailwind CSS

Install tailwindcss and its peer dependencies via npm, and then run the init command to generate both `tailwind.config.js` and `postcss.config.js`.

```markdown
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### Configure your template paths

Add the paths to all of your template files in your `tailwind.config.js` file.

```markdown
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
    "./utils/**/*.{js}",
    "./configs/**/*.{js}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### Add the Tailwind directives to your CSS

Add the `@tailwind` directives for each of Tailwind’s layers to your `./styles/globals.css` file.

```markdown
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Start your build process:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Header

```markdown
Cryptocurrencies
```

```markdown
Digital money for a digital world.
```

```markdown
Cryptocurrencies are digital or virtual currencies that use cryptography for security and are decentralized, meaning they are not controlled by any government or financial institution.
```



## Crypto

Crypto Icon URL: https://s2.coinmarketcap.com/static/img/coins/128x128/1.png

Explorer SVG:

```markdown
<svg
  className="w-5 h-5 ml-2"
  fill="currentColor"
  viewBox="0 0 20 20"
  xmlns="http://www.w3.org/2000/svg"
>
  <path d="M11 3a1 1 0 100 2h2.586l-6.293 6.293a1 1 0 101.414 1.414L15 6.414V9a1 1 0 102 0V4a1 1 0 00-1-1h-5z"></path>
  <path d="M5 5a2 2 0 00-2 2v8a2 2 0 002 2h8a2 2 0 002-2v-3a1 1 0 10-2 0v3H5V7h3a1 1 0 000-2H5z"></path>
</svg>
```

## Crypto Endpoint

Crypto Endpoint URL: https://api.binance.com/api/v3/ticker/24hr?symbols=['ETHUSDC','SOLUSDC']

## Credit

Powered by [Binance](https://www.binance.com)




