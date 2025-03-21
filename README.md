# Fart App Landing Page

A modern landing page built with Next.js and Tailwind CSS.

## Getting Started

### Prerequisites

-   Node.js 18+
-   npm, yarn, or pnpm

### Installation

1. Clone the repository

    ```
    git clone https://github.com/your-username/fart-app-landing.git
    cd fart-app-landing
    ```

2. Install dependencies

    ```
    npm install
    # or
    yarn
    # or
    pnpm install
    ```

3. Start the development server
    ```
    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```

## Deployment

This project can be easily deployed to Vercel using the provided npm scripts:

### Using npm scripts

1. **For production deployment:**

    ```
    npm run deploy
    # or
    yarn deploy
    # or
    pnpm deploy
    ```

    This will deploy your application to production using Vercel.

2. **For test/preview deployment:**
    ```
    npm run test-deploy
    # or
    yarn test-deploy
    # or
    pnpm test-deploy
    ```
    This creates a preview deployment that you can share for testing before going to production.

When running these commands for the first time:

-   You'll be prompted to log in to your Vercel account
-   You'll need to link the project to a Vercel project (create new or select existing)
-   The CLI will guide you through configuring deployment settings

After the initial setup, subsequent deployments will be faster as your project configuration will be saved.

### Using Git Integration

You can also connect your GitHub repository to Vercel for automatic deployments:

1. Push your repository to GitHub
2. Go to [Vercel](https://vercel.com) and create a new project
3. Import your GitHub repository
4. Configure your project settings
5. Deploy

With this setup, new deployments will be created automatically when you push changes to your repository.

## Learn More

-   [Next.js Documentation](https://nextjs.org/docs)
-   [Tailwind CSS Documentation](https://tailwindcss.com/docs)
-   [Vercel Documentation](https://vercel.com/docs)

## License

This project is open source and available under the [MIT License](LICENSE).
