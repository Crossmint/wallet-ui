# wallet-ui

UI components for rendering an NFT wallet, built with TailwindCss

## Purpose

This page views are intended to reduce development time of a whitelabel wallet by providing a set of UI components.

Developers should:
* Reuse and addapt this components to a frontend framework - like React, Angular or Vue
* Deploy a backend to interact with the Crossmint Wallets API

## How to preview

Run a local server from the working directory, using one of the following commands:

Using Python:
```
python3 -m http.server --cgi 8080
```

Using php:
```
php -S localhost:2222
```

Using npm:
```
// Globally install serve
npm i -g serve
// Run serve
serve
```

## Files

```
.
├── LICENSE
├── README.md
├── account.html - _Page with account information_
├── assets
│   ├── ethereum-grey.svg
│   ├── logo.png
│   ├── polygon-grey.svg
│   └── solana-grey.svg
├── collection.html - _NFTs list view, with component to filter by chain_
├── nft.html - _NFTs detail view_
├── nftExport.html - _NFTs detail view, with export modal_
└── nftQR.html - _NFTs detail view, with QR modal_
```