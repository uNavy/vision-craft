# Vision Craft

**Vision Craft** is an AI-powered image processing tool created as a **learning project**. The goal is to explore AI-driven image manipulation, including **image cleansing, aspect ratio adjustments, and more**. Built with **Next.js** and modern frontend technologies.

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features) (Coming soon)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets) (Coming soon)
6. 🔗 [Links](#links) (Coming soon)
7. 🚀 [More](#more) (Coming soon)

## 🤖 Introduction

Vision Craft is designed to provide various AI-powered image processing features such as image enhancement, background removal, and resizing. This project serves as a hands-on learning experience while building a practical SaaS tool.

## ⚙️ Tech Stack

- **Frontend**: Next.js, TypeScript, Shadcn UI  
- **Styling**: Tailwind CSS  
- **Backend**: MongoDB  
- **Authentication**: Clerk  
- **Storage**: Cloudinary  
- **Payments**: Stripe  

## 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/your-repo/vision-craft.git
cd vision-craft

**Installation**

Install the project dependencies using npm:

```bash
npm run dev
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#MONGODB
MONGODB_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com/) and [Stripe](https://stripe.com)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
