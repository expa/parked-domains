## Parked domains

This is a [Next.js](https://nextjs.org/) project that displays a "Coming soon" page for parked domains. This one project can support multiple domains. The correct domain is displayed on the page, metadata and links from the server side.

![spot](https://user-images.githubusercontent.com/81450/118815014-b1af3c00-b8a8-11eb-8e44-eb6f2d1030c8.png)



## Adding new domains

Add new domains to the Vercel project: https://vercel.com/expa/parked-domains/settings/domains

Then point the domains to Vercel's name servers.

```
ns1.vercel.com
ns2.vercel.com
```


## Running locally

After cloning the repositody, run the development server:

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


## Deploy changes

Open a PR with your changes. Vercel will automatically check for any issues and deploy to a temporary server so you can test it live.

Merging your PR into `main` will trigger an automatic deploy to Vercel and make changes available on all domains.

Check https://vercel.com/expa/parked-domains/deployments for deploy status.
