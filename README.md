# Initializing Worker for cloudflare: 

Initializing a worker

To create and deploy your application, you can take the following steps - 

Initialize a worker
bash
```
npm create cloudflare -- my-app
```
Select no for Do you want to deploy your application 
Explore package.json dependencies
"wrangler": "^3.0.0"
Notice express is not a dependency there

Start the worker locally

```
npm run dev
 ```

login and Deploy first "Hello World" project  on cloudflare:

```
npx wrangler login 
npx wrangler whoami
npm run deploy
```
