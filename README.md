This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# Next.js Project Version

## Project Overview
This project is a web application built using **Next.js** and **Tailwind CSS**.

### Version Information

- **Next.js**: 15.3.0
- **React**: 19.1.0
- **React-DOM**: 19.1.0
- **TypeScript**: 5.8.3
- **Tailwind CSS**: 3.3.5

### Dependencies
The project depends on the following packages:

- **@types/node**: 22.14.0
- **@types/react**: 19.1.0
- **@types/react-dom**: 19.1.2
- **eslint**: 9.24.0
- **eslint-config-next**: 15.3.0
- **next**: 15.3.0
- **react**: 19.1.0
- **react-dom**: 19.1.0
- **typescript**: 5.8.3

### Development Dependencies
- **autoprefixer**: ^10.4.21
- **postcss**: ^8.5.3
- **tailwindcss**: ^3.3.5

## Tailwind CSS Version Change Explanation

Initially, the project used **Tailwind CSS v4**. However, due to some bugs and compatibility issues, the team decided to downgrade to **v3.3.5**. The version 3.x series is more stable in the context of this project and has resolved several compatibility issues with other dependencies.

Downgrading to v3 ensures better stability and smoother integration with the existing packages, leading to a more reliable development experience.


## Get Started

### Install Dependencies

```bash
npm install
```


### Create Project
```bash
npm create-next-app@13.4
```

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## shortcut key
rafce -> arrow function component 


## Notes
### CSR VS SSR
![alt text](notes\CSR_VS_SSR.png)

btw, SSR will lose the power of interactivity with clients.

