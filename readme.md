
pnpm create vite
cd upload-ai-web
pnpm install
pnpm run dev

pnpm add -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
pnpm i -D @types/node

pnpm dlx shadcn-ui@latest init
pnpm dlx shadcn-ui@latest add button
pnpm dlx shadcn-ui@latest add separator
pnpm dlx shadcn-ui@latest add textarea
pnpm dlx shadcn-ui@latest add label
pnpm dlx shadcn-ui@latest add select
pnpm dlx shadcn-ui@latest add slider

pnpm i lucide-react
