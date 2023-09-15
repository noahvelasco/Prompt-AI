
# Promptopia

A fullstack web application using the modern NEXT.js React framework. It is a AI chat prompt suggestion generator that uses Google Authentication and MongoDB.

## Tutorial Followed
[Tutorial](https://youtu.be/wm5gMKuwSYk?si=ZFGqPHEJtrENcQFz)

## Preview
 <p align="center">
<img src=".\AppScreenshots\1.png" alt="" height="500"/>
<img src=".\AppScreenshots\2.png" alt="" height="500"/>
<img src=".\AppScreenshots\3.png" alt="" height="500"/>
<img src=".\AppScreenshots\4.png" alt="" height="500"/>
<img src=".\AppScreenshots\5.png" alt="" height="500"/>
</p>


## Prereqs

* Create a MongoDB Account ([As seen here](https://youtu.be/wm5gMKuwSYk?si=ZFGqPHEJtrENcQFz))
* Create a Google Cloud Project ([As seen here](https://youtu.be/wm5gMKuwSYk?si=ZFGqPHEJtrENcQFz))

## Tech Stack

* NEXT.js
* MongoDB
* Tailwind CSS

## Dependencies

* BCrypt Password Hasher
* Mongoose DBMS
* NextAuth.js

## Getting Started

First, create a `.env` file in the root dir and add these variables.

```
GOOGLE_ID=<GOOGLE CLOUD PROJECT ID>
GOOGLE_CLIENT_SECRET=<GOOGLE CLOUD PROJECT ID>
MONGODB_URI=<MONGODB URL>

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=hkmwTmU5v7keN7PO5WiVgXZBgcH9tEXiYEItgoz7Fxs=
```
**([AS SEEN HERE](https://youtu.be/wm5gMKuwSYk?si=ZFGqPHEJtrENcQFz))**

Finally, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Things I learned

* Setting up MongoDB in Next with Mongoose and API calls
* Authentication using NextAuth and Google Cloud OAuth Web Creation
* NEXT.js folder structure/modularization
* NEXT.js NextAuth Session
* Tailwind Styling
