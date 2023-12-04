Project: Clerk-Auth (EDIT THIS FILE IN VSCODE)
(Simple Next.js & React Authentication With Clerk)
C:\wampp64\www\projects4\clerk-auth\

-----------------------------------------------------------------------------------------------------
PURPOSE:
Clerk Authentication App, Next.js app that uses Clerk.com for authentication and user management.
-----------------------------------------------------------------------------------------------------
STATUS: TEMPLATE, DEVELOPMENT, BACKED UP

DATE: 12/03/2023

-----------------------------------------------------------------------------------------------------
PACKAGE.JSON
  {
  "name": "clerk-auth",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "@clerk/nextjs": "^4.27.3",
    "next": "14.0.3",
    "react": "^18",
    "react-dom": "^18"
  },
  "devDependencies": {
    "autoprefixer": "^10.4.16",
    "postcss": "^8.4.32",
    "tailwindcss": "^3.3.5"
  }
}

----------------------------------------------------------------------------------------------------
NOTEs(!)
1- Run $npm run dev startup.
2- Couldn't get the custom register form to work. Errors, see REFFERENCES below.

----------------------------------------------------------------------------------------------------
TODO's:
1- Deploy / build to GitHub Pages.

----------------------------------------------------------------------------------------------------
REFERENCES / SOURCES / LINKS:

Travercy Media Tutorial Video (Simple Next.js & React Authentication With Clerk):
https://www.youtube.com/watch?v=RHFmsoiVtKE

Clerk | Rate Limits:
https://clerk.com/docs/backend-requests/resources/rate-limits

Clerk | Error Handling:
https://clerk.com/docs/custom-flows/error-handling

GitHUB SOURCE:
https://github.com/bradtraversy/clerk-app/tree/main

GitHUB PAGES:

----------------------------------------------------------------------------------------------------
MODIFICATIONS:

----------------------------------------------------------------------------------------------------
env.local

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_Y29uY3JldGUtc3VuYmVhbS00MS5jbGVyay5hY2NvdW50cy5kZXYk
CLERK_SECRET_KEY=sk_test_EWCF7OdRjIQrtNUBdfaYHjUK5Xul6NS9pEmYQzMArn

----------------------------------------------------------------------------------------------------