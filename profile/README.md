# Welcome to Webnative Examples!

Webnative is [Fission](https://fission.codes)'s true local-first, edge computing stack. Webnative empowers you to build fully distributed web applications with auth and storage without needing a complex backend. To learn more, check out [the Fission Guide to Webnative](https://guide.fission.codes/developers/webnative).

In this organization, you'll find templates for quickly getting started with Webnative and reference examples of apps built using Webnative.

## Key Repositiories

### Webnative App Template

The Webnative App Template repositories are clone-and-go templates for building a web application using Webnative, fast. The templates are "batteries included", and include user accounts, authorization, encrypted file storage, and key management via device linking.

The templates come in two authentication flavors and are implemented in two different front-end frameworks:

**WebCrypto-based Auth**

The base [Webnative authentication scheme](https://guide.fission.codes/developers/webnative/auth) uses private keys stored using the browser's [WebCrypto API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API).

- [`webnative-app-template`](https://github.com/webnative-examples/webnative-app-template) - A Webnative App Template written in Svelte + TypeScript.
- [`webnative-app-template-react`](https://github.com/webnative-examples/webnative-app-template-react) - A Webnative App Template written in React + TypeScript.

**WalletAuth**

WalletAuth is for building apps where the user will log in with MetaMask or another in-browser crypto wallet.

- [`walletauth`](https://github.com/webnative-examples/walletauth) - A WalletAuth template, written in Svelte + TypeScript.
- [`walletauth-react`](https://github.com/webnative-examples/walletauth-react) - A WalletAuth template, written in React + TypeScript.

### Create Webnative App

[`create-webnative-app`](https://github.com/webnative-examples/create-webnative-app) is a CLI generator that allows you to spin either React or SvelteKit flavours of Fission's Webnative App Template and Webnative WalletAuth repos.

You can find other examples of Webnative applications in [the Fission organization](https://github.com/fission-codes).
