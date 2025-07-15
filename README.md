This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started
# 🎬 Netflix Clone

A full-stack **Netflix Clone** built with the latest modern technologies like **Next.js 14**, **Prisma**, **NextAuth**, and **Tailwind CSS**. This app includes authentication, UI components, and database integration for a fully responsive movie streaming experience.

---

## 🚀 Tech Stack

| Layer        | Technologies Used                                                                 |
|--------------|------------------------------------------------------------------------------------|
| Frontend     | Next.js 14, React 18, Tailwind CSS, Radix UI, Lucide Icons, clsx, cva             |
| Backend      | Next.js API Routes, NextAuth for authentication, Prisma as ORM                    |
| Auth         | NextAuth with Prisma Adapter, Credentials & OAuth Providers                       |
| Database     | PostgreSQL (local or remote), managed with Prisma                                 |
| Styling      | Tailwind CSS, tailwindcss-animate, class-variance-authority (CVA), clsx           |
| Mail (SMTP)  | Mailtrap (for development/testing), Nodemailer, Resend (optional email support)   |
| TypeScript   | Full support with type safety and ESLint configuration                            |

---

## ⚙️ Project Setup

1. **Clone the repository**
```bash
git clone https://github.com/umar591/Netflix-Clone-.git
cd netflix-clone



## 🔐 Environment Variables (.env)

Create a `.env` file in the root directory and define the following environment variables:

```env
# ✅ PostgreSQL Database URL (update with your DB credentials)
DATABASE_URL=postgresql://USER:PASSWORD@HOST:PORT/DATABASE_NAME

# ✅ Mailtrap SMTP Configuration
EMAIL_SERVER_HOST=sandbox.smtp.mailtrap.io
EMAIL_SERVER_PORT=2525
EMAIL_SERVER_USER=YOUR_MAILTRAP_USERNAME
EMAIL_SERVER_PASSWORD=YOUR_MAILTRAP_PASSWORD

# ✅ NextAuth Config
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=YOUR_RANDOM_SECRET


First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
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
