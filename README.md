This is a [Next.js](https://nextjs.org/) project 

## Introduction

This repository contains a Todo application built using the latest features of Next.js 13. The project is designed to demonstrate the capabilities of Next.js 13 by utilizing its features to build a functional Todo application.

## Features

- **Next.js 13**: The latest version of Next.js, which includes features like server components, improved routing, and better performance.
- **Todo Application**: A simple yet functional Todo application that allows users to check Next.js 13's feature.
- **Prisma**: build simple database for this project working.

## Usage

- To add a task, enter the task description in the input field and click on the 'Create' button.

- ![image](https://github.com/darecallad/NextJs13featureProject/assets/27443134/90f7f35d-909d-45b4-b58e-8d9084027cea)

- ![image](https://github.com/darecallad/NextJs13featureProject/assets/27443134/4b89be29-78fc-4263-870b-c57cdbdeec48)

- To mark a task as completed, click on the checkbox next to the task description.

- ![image](https://github.com/darecallad/NextJs13featureProject/assets/27443134/56704bd8-106f-4826-bbf8-63f5dd71555c)


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Next.js 13

# Improved File-Based Routing

Next.js has always had a file-system based router built on the file system, but in Next.js 13, it has been improved to work more intuitively with folders.

# Folder-Based Dynamic Routes

In Next.js 13, you can create dynamic routes using folders. For example, if you have a file structure like this:

diff
Copy code
pages/
--| user/
-----| [id].js
The [id].js file inside the user folder will automatically be a dynamic route that matches user/1, user/2, etc.

# Linking Between Pages

To link between pages, you can use the Link component from next/link. For example:

import Link from 'next/link'

![image](https://github.com/darecallad/NextJs13featureProject/assets/27443134/ce9962bb-a340-48b5-a86c-1acbbff020be)

## Getting Started

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

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
