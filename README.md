This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/zeit/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm i
npm run dev
# or
yarn
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

For an optimized build (this is the only build that supports offline access), please make sure to run:

```bash
npm run build
npm run start
# or
yarn build
yarn start
```

## TODO

[x] Simple fetch using SWR (took ~ 1 hour)
[x] Infinite Pagination using useSWRPages() & IntersectionObserver (took ~3 hours)
[x] Offline support using next-offline (took ~3 hours)
[x] Styling using Tailwind (took ~2 hours)
[ ] Cypress Testing
[ ] react-testing-library