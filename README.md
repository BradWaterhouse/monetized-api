## API Monetization Proof of concept

## Run

- Create a metered billing product in Stripe
  - https://dashboard.stripe.com
- Install Stripe CLI
  - https://stripe.com/docs/stripe-cli
- Add your testing Stripe secret key in the index.js

```bash
git clone 
npm i
node .
stripe listen --forward-to localhost:8888/webhook
```
