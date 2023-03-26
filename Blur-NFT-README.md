# Moralis Blur NFT Marketplace Clone - \_published Sat Mar 25, 2023

After intro, [Tutorial starts at (4:13)](https://youtu.be/WVEqX8DL4KE?t=253).

1. Create backend directory in our project directory
2. Set up front end with `npx create-next-app@latest`

   > `npx create-next-app@latest`

   - See [Next Docs on Create Next App](https://nextjs.org/docs/api-reference/create-next-app).
   - _What is name of project_ = `frontend`
   - Answer `NO` to all the questions.
   - _What **import alias** would you like configured?_ = **Just hit return to bypass**

3. cd into `backend` directory and run `npm init -y`

   > `npm init -y`

**RETURNS:**

```js
$ npm init -y
Wrote to C:\Users\Blockchain Data API\Documents\Blockchain_Dev\Moralis-YouTube\Blur-NFT-Marketplace-Clone\blur-nft-clone\backend\package.json:
  "keywords": [],
  "author": "",
  "license": "ISC"
}

```

- Install a few dependencies:
- We want an express server.
- We want dotenv
- We want Cors
- We'll want Moralis (API)
- `npm i express dotenv cors moralis` - (4:49)
