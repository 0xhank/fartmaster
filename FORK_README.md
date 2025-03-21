### Step 1: Fork the Repository

First, fork the repository to your GitHub account.

```
https://github.com/0xhank/fartmaster
```

### Step 2: Clone Your Fork

Clone your forked repository to your local machine.

```
git clone https://github.com/YOUR_USERNAME/fartmaster
cd fartmaster
```

### Step 3: Install Dependencies

Install the necessary dependencies using your preferred package manager.

Using pnpm:

```
pnpm install
```

### Step 4: Start Development Server

Run the development server to start making changes.

Using pnpm:

```
pnpm dev
```

### Step 5: Start Customizing

You can now start customizing the template for your needs. Here are the main files to look at:

-   `src/components/` - UI components
-   `src/pages/` - Page components
-   `src/styles/` - CSS styles
-   `public/` - Static assets

### Step 6: Deploy

You can easily deploy this project to Vercel using the provided npm scripts:

1. **Setup Vercel CLI** (if not already installed):

    ```
    pnpm install
    ```

    (Vercel CLI is included as a dev dependency)

2. **For production deployment:**

    ```
    pnpm deploy
    ```

    This will deploy your application to production using Vercel.

3. **For test/preview deployment:**
    ```
    pnpm test-deploy
    ```
    This creates a preview deployment that you can share for testing before going to production.

When running these commands for the first time:

-   You'll be prompted to log in to your Vercel account
-   You'll need to link the project to a Vercel project (create new or select existing)
-   The CLI will guide you through configuring deployment settings

After the initial setup, subsequent deployments will be faster as your project configuration will be saved.

Alternatively, you can connect your GitHub repository to Vercel for automatic deployments when you push changes to your repository.
