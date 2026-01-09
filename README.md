# Zombie Mayhem

A zombie shooting game refactored for Vercel deployment.

## Project Structure

- `index.html`: The main game interface.
- `script.js`: Game logic (jQuery + CreateJS).
- `style.scss`: Game styles (Sass).
- `style.css`: Compiled styles.
- `package.json`: Dependencies and build scripts.

## How to Run Locally

1.  Install dependencies:
    ```bash
    npm install
    ```

2.  Start the development server:
    ```bash
    npm start
    ```
    This will serve the game at `http://localhost:3000`.

## How to Deploy to Vercel

1.  Install the Vercel CLI (optional, if you want to deploy from CLI):
    ```bash
    npm i -g vercel
    ```

2.  Run the deploy command:
    ```bash
    vercel
    ```

3.  **Alternatively (Git Integration):**
    - Push this repository to GitHub/GitLab/Bitbucket.
    - Import the project into Vercel.
    - Vercel will automatically detect the settings.
    - **Build Command:** `npm run build`
    - **Output Directory:** `.` (root)

## Development

To make changes to the CSS, edit `style.scss` and re-run the build:

```bash
npm run build
```
