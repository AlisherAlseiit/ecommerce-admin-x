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
After adding new models to PRISMA follow these steps:
1. npx prisma generate
2. npx prisma db push


---
1. npm i axios
2. npm i react-hot-toast

---
Reset db
1. npx prisma migrate reset
2. yes

1. npx prisma generate
2. npx prisma db push


1. npx shadcn-ui@latest add popover
2. npx shadcn-ui@latest add popover

1. npx shadcn-ui@latest add separator

1. npx shadcn-ui@latest add alert
2. npx shadcn-ui@latest add badge


---
TO work with Cloudinary
link: https://next.cloudinary.dev/installation

1. npm install next-cloudinary
2. add NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME="<Your Cloud Name>" to .env
3. don't forget to add code (modify) next.config.js and add this line:
images: {
    domains: [
      "res.cloudinary.com"
    ]
  }

---
you can take uploadPreset:
1. go to cloudinary website
2. settings
3. upload
4. upload presets
5. should be unsigned always



