# Fumadocs OpenAPI Error

1. Download the repo 
2. install deps
3. pnpm dev
4. navigate to http://localhost:3000/docs/show-consent-banner


```
TypeError: Cannot read properties of undefined (reading 'type')
    at resolveErrorDev (webpack-internal:///(app-pages-browser)/../node_modules/.pnpm/next@15.3.2_@babel+core@7.26.10_@opentelemetry+api@1.9.0_react-dom@19.1.0_react@19.1.0__react@19.1.0/node_modules/next/dist/compiled/react-server-dom-webpack/cjs/react-server-dom-webpack-client.browser.development.js:1865:46)
    at processFullStringRow (webpack-internal:///(app-pages-browser)/../node_modules/.pnpm/next@15.3.2_@babel+core@7.26.10_@opentelemetry+api@1.9.0_react-dom@19.1.0_react@19.1.0__react@19.1.0/node_modules/next/dist/compiled/react-server-dom-webpack/cjs/react-server-dom-webpack-client.browser.development.js:2245:17)
    at processFullBinaryRow (webpack-internal:///(app-pages-browser)/../node_modules/.pnpm/next@15.3.2_@babel+core@7.26.10_@opentelemetry+api@1.9.0_react-dom@19.1.0_react@19.1.0__react@19.1.0/node_modules/next/dist/compiled/react-server-dom-webpack/cjs/react-server-dom-webpack-client.browser.development.js:2233:7)
    at progress (webpack-internal:///(app-pages-browser)/../node_modules/.pnpm/next@15.3.2_@babel+core@7.26.10_@opentelemetry+api@1.9.0_react-dom@19.1.0_react@19.1.0__react@19.1.0/node_modules/next/dist/compiled/react-server-dom-webpack/cjs/react-server-dom-webpack-client.browser.development.js:2479:17)



    at APIPage (rsc://React/Server/webpack-internal:///(rsc)/./mdx-components.tsx?18:20:102)
    at _createMdxContent (rsc://React/Server/webpack-internal:///(rsc)/./content/docs/(api)/show-consent-banner.mdx?collection=docs&hash=1747227317554?16:46:74)
    at MDXContent (rsc://React/Server/webpack-internal:///(rsc)/./content/docs/(api)/show-consent-banner.mdx?collection=docs&hash=1747227317554?17:79:16)
    at Page (rsc://React/Server/webpack-internal:///(rsc)/./app/docs/%5B%5B...slug%5D%5D/page.tsx?14:47:102)
```
