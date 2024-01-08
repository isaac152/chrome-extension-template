This is a Chrome extension base template that uses:

- Tailwindcss
- Plasmo
- React
- Typescript
- Playwright

## Getting Started

First install the dependencies:

```bash
pnpm install
```

Install the dependencies for run the tests:

```bash
    playwright install --with-deps chrome
    # or 
    pnpm exec playwright install --with-deps chrome
```


Then run the development server:

```bash
pnpm dev
# or
npm run dev
```

Open your browser and load the appropriate development build.


## Making production build

Run the following:

```bash
pnpm build
# or
npm run build
```

This should create a production bundle for your extension, ready to be zipped and published to the stores.
