# Twitter Clone
This project is a Twitter clone built using Next.js, Tailwind CSS, MongoDB, Prisma, NextAuth.js, and TypeScript.

## Demo
Check out the below pics ![Sign In](sign-in.png) ![UI](ui.png) ![Profile](profile.png) ![Profile Pic](profilepic.png) ![Bookmarks](bookmarks.png)

## OVerview
The Twitter Clone project is aimed at replicating the core functionalities of Twitter. It allows users to post tweets, follow other users, like tweets, and view their timeline. The application utilizes modern web development technologies and follows best practices for scalability and maintainability.

## Run Locally

### Clone the project

```bash
git clone https://github.com/AnandIndraganti/xtakes.git
```

### Go to the project directory

```bash
cd xtakes
```

### Install dependencies

```bash
npm install
```

### Get the Database ready
For Setting up database locally using docker
Follow : https://github.com/prisma/prisma/discussions/18958 
Connect through one of the following:
```bash
mongodb://localhost:27017,localhost:27018,localhost:27019/?replicaSet=myReplicaSetName
mongodb://localhost:27017,localhost:27018,localhost:27019/my-database-name?replicaSet=myReplicaSetName
```

### Set up the .env File

```bash
DATABASE_URL=mongodb://localhost:27017,localhost:27018,localhost:27019/?replicaSet=myReplicaSetName
NODE_ENV=development
GOOGLE_CLIENT=your_google_cloud_web_client_id
GOOGLE_SECRET=your_google_cloud_web_client_secret
JWT_SECRETyour_jwt_secret_password
```
### First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
