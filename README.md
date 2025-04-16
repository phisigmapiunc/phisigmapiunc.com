# Phi Sigma Pi Alpha Kappa Chapter

UNC's Gender-Inclusive National Honor Fraternity, Phi Sigma Pi (PSP) is an inclusive organization dedicated to: promoting lifelong learning, inspiring Members to lead, and cultivating lasting fraternal bonds, while always conducting our lives with honor. We commit ourselves to a life of social service with the goal of improving humanity through our principles: Scholarship, Leadership, and Fellowship.

The website for the Alpha Kappa Chapter is located at the domain `phisgimapiunc.com`, which is currently an older version of this website while this one is being created.

## Get Programming

This web app is programmed using [Next.js](https://nextjs.org/docs) and [Supabase](https://supabase.com/docs/reference/javascript/start).

> Note: In order to run with a working backend, you will need to obtain access to the subabase URL and KEY from Andrew or as the current PSP IT Chair.

1. Download [node.js](https://nodejs.org/en)
2. Run `cd psp-next-app` to change directories
3. Run `npm install` to install the node packages
4. Copy the `URL` and `ANON` `PUBLIC` Key from the [Project Page](https://app.supabase.com/project/_/settings/api).

5. Place them in a new file in this directory called `.env.local` with the contents:

```text
NEXT_PUBLIC_SUPABASE_URL=<URL you copied>
NEXT_PUBLIC_SUPABASE_ANON_KEY=<ANON PUBLIC key you copied>
```

6. In the same directory, run `npm run dev` to run the development server.
7. Open the local version of the website at [http://localhost:3000](http://localhost:3000)
8. Dev away!

## Developer Documentation

- [Design Document](./docs/design-doc.md)
