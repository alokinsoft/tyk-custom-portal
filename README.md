## Running the portal

- Clone this repository
- Make a copy of env.sample -> .env
- Setup values for the API Key and Dashboard URL
- Run `docker-compose up`
- Custom Dashboard is available at `localhost:8000`


## Why?
Tyk Dashboard by default include nice developer portal functionality, but in some cases it is require to have custom logic or, for example, embed portal into existing platform. Thankfully Tyk is flexible enough to provide an easy way of integrating portal to any platform and language using a few API calls.

Screencast covering process of building custom portal: https://tyk.io/docs/tyk-developer-portal/customise/custom-developer-portal/#why-build-a-custom-developer-portal

Please also check the page above for full documentation.
