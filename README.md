
# Evently 

Evently is Next JS web application which manages events. User can create, update, book event.


## Features

- Authentication with clerk api
- Create Event
- Payment with Stripe to book events
- Filtering the events
- uploadthing to upload the events
-  Tailwind CSS & Shadcn
-  React Hook Form
-  React-Datepicker
- MongoDB


## Run Locally

Clone the project

```bash
  git clone https://github.com/UjwalPatel05/ems.git
```

Install dependencies

```bash
  npm install
```

Setup .env file
```bash
#NEXT
NEXT_PUBLIC_SERVER_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#MONGODB
MONGODB_URI=

#UPLOADTHING
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=

```

Start the server

```bash
  npm run dev
```


## Screenshots

Dashboard
![Dashboard](https://res.cloudinary.com/djstjnl11/image/upload/v1704864521/zvtf0d9mdufzrjcgxzfu.png)

![Dashboard](https://res.cloudinary.com/djstjnl11/image/upload/v1704864521/feilk9opbvfevni5wlv1.png)

Create Event Page
![Create Event](https://res.cloudinary.com/djstjnl11/image/upload/v1704864521/od4lgfenanwg3b6dyryy.png)

Event Page
![Dashboard](https://res.cloudinary.com/djstjnl11/image/upload/v1704864522/iraqiiubgpkm0wsbnvqw.png)

Profile Page
![Profile Page](https://res.cloudinary.com/djstjnl11/image/upload/v1704864522/npfgc5rov2hq8i1yqrpd.png)

Payment with Stripe
![STripe](https://res.cloudinary.com/djstjnl11/image/upload/v1704864522/kjvhgtmcpz2dz5zqiecj.png)

Orders Page
![Orders](https://res.cloudinary.com/djstjnl11/image/upload/v1704864522/qry26bt4rtqagrbcrzcd.png)