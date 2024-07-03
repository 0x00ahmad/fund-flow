# Fund Flow

This is a brief showcase of a full-stack crowdfunding platform that I have built with NextJS using TypeScript

## Technologies

- NextJS
- TailwindCSS
- Drizzle ORM ~ PostgreSQL (NeonDB)
- Redis
- Vitest for unit tests
- ... And much more

## Structure

The project is written in a monorepo, divided into 4 apps:
- user
- admin
- blog
- support

And there are multiple packages like:
- db
- redis
- lib
- ... Many more

To follow DRY principles and re-use logic between the 4 apps.

## Features

- Fundraising Campaign listing
- Campaign creation and management
- Bank account management
- Payouts management
- Admin & Accounting Dashboard for management and platform supervision
- MDX based blog app to write and publish blog posts
- MDX based Help & Suppport app to write and publish articles for users
- Donation functionality
  - (made to integrate any payment provider, such as Stripe, Ayden etc. in under 5-10 minutes)

## Sounds cool, where can I see it?

You can check it out in action on:

[Demo frontend](https://fundflowtheta.vercel.app)
[Demo blog](https://fundflowblog.vercel.app)
[Demo support site](https://fundflowsupport.vercel.app)
[Demo Admin](https://fundflow-backend-admin.vercel.app)

## Where's the source code?

I don't plan to release the source code to public for a handful of reasons, but if you're willing to build/run such a platform for yourself. Then contact me on contact@ahmadrehan.com and we can discuss on your building you your desired platform!

