<p align="center">
  <a href="https://vite.dev/" target="blank"><img src="https://vite.dev/logo.svg" width="120" alt="Vite Logo" /></a>
</p>

# Hive Track

## Description

The frontend for the Hive Track project, built with React, TypeScript and Vite.

## Project Setup

1. **Run the project in development mode**:

   Make sure you have Node.js and npm installed on your machine. Then, install all the required dependencies by running:

   ```bash
   npm install
   ```

2. **Add environment variables**:

   Create a .env file at the root of your project (if not already created) and include the following:

   - BACKEND_URL: Connection string to the backend API.

   ```bash
   BACKEND_URL="https://url-to-your-back.com/"
   ```

3. **Run the development serveur**:

   Start the development serveur with the following command and open the application in your browser at http://localhost:5173.

   ```bash
   npm run dev
   ```

## Available scripts

1. **Run the project in development mode**:

   ```bash
   npm run dev
   ```

2. **Run the project in production preview**:

   ```bash
   npm run preview
   ```

3. **Build for production**:

   ```bash
   npm run build
   ```

4. **Lint the code**:

   ```bash
   npm run lint
   ```

## Project structure

```bash
/src
  /assets       # Static files like images, fonts, etc.
  /components   # React components
  /hooks        # Custom React hooks
  /pages        # Page components
  /services     # API services and data fetching logic
  /types        # TypeScript types and interfaces
  /utils        # Helper functions
  App.tsx       # Root component of the app
  index.css     # Global styles
  main.tsx      # Main entry point of the app
  vite-end.d.ts #TypeScript declaration file for Vite
/public         # Public assets, etc.
```

## Libraries and technologies

- React: A JavaScript library for building user interfaces.
- TypeScript: A typed superset of JavaScript that provides optional static typing.
- Vite: A fast, opinionated build tool that serves the project in development mode and bundles it for production.
- ESLint: A static code analysis tool for identifying problematic patterns in JavaScript and TypeScript code.
- React Router: For handling routing in the app.
- Axios: For making HTTP requests to the backend.
- Tailwind CSS: For styling.

## Deployment

For deploying the frontend, you can use services like [Vercel](https://vercel.com/home), [Netlify](https://www.netlify.com/) or [AWS Amplify](https://aws.amazon.com/amplify/).
Refer to the respective documentation of your chosen service for specific deployment steps.

## Resources

- [Vite Documentation](https://vite.dev/guide/) — Official documentation.

## License

This project is licensed under the MIT License.

## Stay in Touch

- Author: [Jonas Szigeti](https://www.linkedin.com/in/jonas-szigeti/)
- Website: [jsproject.fr](https://jsproject.fr/)
