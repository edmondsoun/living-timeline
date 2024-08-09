LIVING TIMELINE
===============

This is a timeline and memory-keeping tool. It is both simple and highly
configurable, allowing the user to introduce layers of complexity that will best
suit their needs.

Getting Started
---------------

To run the project locally:

```zsh
# Install dependencies:
~ npm -i

# Start dev server:
~ npm run dev
```

This project currently uses a remote database hosted on Vercel for development. Please contact project owners for credentials.

<!-- NOTE: I believe on our current Prisma hobby plan, only the project owner can push schema updates. I'm opening a ticket to confirm this. -->

To create new tables:

```zsh
npx prisma db push
```

Make sure to update the Prisma client when the schema file is changed:

```zsh
npx prisma generate
```

<!-- TODO: Update with DB connection instructions once we have linked Vercel accounts. -->