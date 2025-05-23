Our Smart Inventory Management System is designed to assist small-scale business stores in optimizing their inventory processes. It helps with restocking, trend analysis, and maintaining good sales using AI-driven insights. The system provides real-time stock monitoring, demand forecasting, and automated alerts to prevent overstocking or shortages.

### Tech Stack

Frontend: TypeScript, TailwindCSS, Shadcn UI, Next.js, TanStack Query
Backend: TypeScript, Next.js Route Handlers, Drizzle ORM
Database: Neon PostgreSQL
Authentication: Clerk
Deployment & Hosting: Vercel
This solution aims to improve efficiency and decision-making for store owners, reducing manual workload and enhancing profitability.

## Getting Started

### Install pnpm:

On Windows in PowerShell:

```bash
Invoke-WebRequest https://get.pnpm.io/install.ps1 -UseBasicParsing | Invoke-Expression
```

On Unix systems (macOS/Linux):

```bash
curl -fsSL https://get.pnpm.io/install.sh | sh -
```

### Run locally

Install packages:

```bash
pnpm install
```

Then, run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

### Dev Setup

Install the recommended extensions if you are Using VSCode:

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Tailwind CSS](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

### Project Structure

The following is an overview of the project structure:

inventrack/

├── app/  
│ ├── layout.tsx  
│ ├── page.tsx  
│ └── ...  
├── public/  
├── styles/  
│ ├── globals.css  
│ └── ...  
├── components/  
├── lib/  
├── hooks/  
├── pages/  
├── .eslintrc.js  
├── .prettierrc  
├── tailwind.config.js  
├── tsconfig.json  
├── package.json  
├── pnpm-lock.yaml  
└── README.md

### Contributing

Fork the repository and clone it to your local machine. Create a new branch for your changes:

```bash
git checkout -b my-new-branch
```

Add upstream:

```bash
git remote add upstream https://github.com/zytact/hackdays.git
```

Before pushing your changes, pull the latest changes from upstream:

```bash
git pull upstream main
```

and check for linting errors with the following command:

```bash
pnpm lint
```

make sure to format:

```bash
pnpm format
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
