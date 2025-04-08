# 📌 Next.js Todo App with Google Authentication & PostgreSQL (Prisma)

This is a full-stack **Next.js** application that features a robust **authentication system** using **NextAuth.js**, with support for both **Google OAuth** and **credential-based login**. It uses **Prisma ORM** to manage a **PostgreSQL** database and is ideal for scalable and secure production-ready projects.

---

## 🚀 Tech Stack

- **Framework:** [Next.js 13+](https://nextjs.org/)
- **Authentication:** [NextAuth.js](https://next-auth.js.org/)
- **ORM:** [Prisma](https://www.prisma.io/)
- **Database:** PostgreSQL
- **OAuth Provider:** Google
- **Language:** TypeScript
- **Styling:** Tailwind CSS (optional, if used)

---

## 🔧 Environment Setup

Before running the app, create a `.env.local` file in the root directory and add the following variables:

```env
GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
GOOGLE_REDIRECT_URI=http://localhost:3000/auth/google/callback

POSTGRES_PRISMA_URL=postgresql://postgres:postgres@localhost:5432/postgres?connection_limit=1

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secure-random-secret
