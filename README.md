# Amazon Clone

A fully functional amazon clone with ecommerce functionality made using Next.Js 13. Tailwind CSS has been used to as a CSS framework to style the components. Stripe payment getaway is used. Webhook is used to get the success data from stripe and using it to save the orders in the firebase firestore. Google NextAuth implemented for logging in using google. 

# Installation Steps



## Using npm

Run commands

1) ```npm install```


2) ```npm run dev```

Set Up .env.local

```
# Authentication
GOOGLE_ID = <google_id>
GOOGLE_SECRET = <google_secret>
NEXTAUTH_URL = http://localhost:3000
NEXTAUTH_SECRET = <nextauth_secret>

# Stripe
STRIPE_PUBLIC_KEY = <stripe_public_key>
STRIPE_SECRET_KEY = <stripe_secret_key>

# Stripe Terminal/CLI
STRIPE_SIGNING_SECRET = <stripe_signing_secret>
 
HOST = http://localhost:3000

# Need to add this to... google cloud
# http://localhost:3000/api/auth/callback/google
```


