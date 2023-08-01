links:

1. https://ui.shadcn.com/docs
2. https://dashboard.clerk.com/

3. npx create-next-app@latest ecommerce-admin-x --typescript --tailwind --eslint

√ Would you like to use `src/` directory? ... No
√ Would you like to use App Router? (recommended) ... Yes
√ Would you like to customize the default import alias? ... No

2. npx shadcn-ui@latest init
   √ Would you like to use TypeScript (recommended)? ... yes
   √ Which style would you like to use? » Default
   √ Which color would you like to use as base color? » Slate
   √ Where is your global CSS file? ... app/globals.css
   √ Would you like to use CSS variables for colors? ... yes
   √ Where is your tailwind.config.js located? ... tailwind.config.js
   √ Configure the import alias for components: ... @/components
   √ Configure the import alias for utils: ... @/lib/utils
   √ Are you using React Server Components? ... yes
   √ Write configuration to components.json. Proceed? ... yes

3. npm install @clerk/nextjs
4. npx shadcn-ui@latest add dialog
5. npm install zustand
6. npx shadcn-ui@latest add form
7. npx shadcn-ui@latest add input

---
to work with prisma
1. npm i -D prisma
2. npm i @prisma/client
3. npx prisma init
4. added prisma.db.ts under lib folder
5. added DATABASE_URL in .env
6. go to https://planetscale.com/, create database
7. added code in schema.prisma file
8. run npx prisma generate
9. npx prisma db push

---
1. npm i axios
2. npm i react-hot-toast

---
Reset db
1. npx prisma migrate reset
2. yes

1. npx prisma generate
2. npx prisma db push

