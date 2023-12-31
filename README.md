{
  "name": "degen-gatsby",
  "version": "1.0.0",
  "private": true,
  "description": "degen-gatsby",
  "author": "dhow",
  "keywords": [
    "gatsby"
  ],
  "scripts": {
    "develop": "gatsby develop",
    "start": "gatsby develop",
    "build": "gatsby build",
    "serve": "gatsby serve",
    "clean": "gatsby clean",
    "deploy": "gatsby build --prefix-paths && echo 'degentoken.xyz' > ./public/CNAME && gh-pages -d public",
    "typecheck": "tsc --noEmit",
    "cypress:open": "cypress open"
  },
  "dependencies": {
    "@chakra-ui/gatsby-plugin": "^2.0.4",
    "@chakra-ui/icons": "^1.1.7",
    "@chakra-ui/react": "^1.8.5",
    "@emotion/react": "^11.8.1",
    "@emotion/styled": "^11.8.1",
    "@fontsource/roboto-mono": "^4.5.3",
    "@fontsource/space-mono": "^4.5.2",
    "@json-rpc-tools/utils": "^1.7.6",
    "@mdx-js/mdx": "^1.6.22",
    "@mdx-js/react": "^1.6.22",
    "@randlabs/myalgo-connect": "^1.1.2",
    "@walletconnect/client": "^1.7.1",
    "algorand-walletconnect-qrcode-modal": "^1.6.1",
    "algosdk": "^1.13.1",
    "camelcase-keys": "^7.0.2",
    "crypto-browserify": "^3.12.0",
    "framer-motion": "^6.2.8",
    "gatsby": "^4.8.0",
    "gatsby-plugin-image": "^2.8.1",
    "gatsby-plugin-mdx": "^3.8.1",
    "gatsby-plugin-react-helmet": "^5.8.0",
    "gatsby-plugin-sharp": "^4.8.1",
    "gatsby-plugin-sitemap": "^5.8.0",
    "gatsby-source-filesystem": "^4.8.1",
    "gatsby-transformer-sharp": "^4.8.0",
    "react": "^17.0.1",
    "react-dom": "^17.0.1",
    "react-helmet": "^6.1.0",
    "react-icons": "^4.3.1",
    "react-infinite-scroll-component": "^6.1.0",
    "stream-browserify": "^3.0.0",
    "use-persisted-state": "^0.3.3"
  },
  "devDependencies": {
    "@types/node": "^17.0.14",
    "@types/react": "^17.0.38",
    "@types/react-dom": "^17.0.11",
    "@types/react-helmet": "^6.1.5",
    "@types/use-persisted-state": "^0.3.1",
    "cypress": "^9.5.1",
    "gh-pages": "^3.2.3",
    "typescript": "^4.5.5"
  }
}
