## Node v18.12.0 -> not working 
## Node v16.16.0 -> working 
## Need to work on find google api seems its expired


## Its a Vanilla JS project


# Book Finder App 🌴🌴🌴
# A very simple book finder using google books api

- Includes webpack HMR
- Webpack 4
- Es6 / Babel
- Webpack CSS loader / Style loader

Please keep in mind, This is a helper for me to tinker with ideas and start projects from - I've tried to keep it as clean as possible. Add your own packages to suit your own workflow. The one thing I've ommited is `package-lock.json` generation. But you can add this back in by removing `.npmrc` before running `npm i`

### First

Install deps from project root `yarn` or `npm i`

### Start development server with:

`yarn start` or `npm run start`

It's possible to use a different port by specifying this first like so: 

`CVA_PORT=7788 yarn start` to start with port 7788. Same for npm just include `CVA_PORT=7788` at the beginning.

### Build for production

`yarn build` or `npm run build`

### Once website loads
1) type any keyword and hit enter
