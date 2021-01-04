# Code Challenge 6
## Earls Restaurant Eating Like Canadians
1. Began my creating a **New Repo** called **code challenge 6**
2. Cloned new repo to my desktop, using **iTerm**
   ### Example
   * git clone (new repo address)

3. Once new repo was cloned I began adding files as well as ran proper commands so code challenge 6 would be able to open with live-server, dependencies, dev's etc.
   ### Example
   * yarn add -D live-server && yarn add tailwindcss postcss autoprefixer && git init && code .
   * Made sure package.json looks like this
     * {
       *  "devDependencies": {
       *  "live-server": "^1.2.1"
       *  },
       *  "dependencies": {
       *  "autoprefixer": "^10.1.0",
       *  "postcss": "^8.2.1",
       *  "tailwindcss": "^2.0.2"
       *  },
       *  "scripts": {
       *  "dev" : "live-server .",
       *  "build" : "tailwindcss build ./src/tailwind.css -o ./dist/style.css"
       *  },
     * }

   * npx tailwindcss init , either in iTerm2 or terminal within VScode
   * Create tailwind.css file inside of src/ folder
   * Paste styles in tailwind.css file, see below
     @tailwind base;
     @tailwind components;

     /**
     Custom CSS

     */

     @tailwind utilities;
   * yarn run build

4. Once commands, files etc. were completed I began working on building earls.ca website as well as the accessibility icon
5. Not able to deploy to Vercel, searching online for reason. Error received: Error: No Output Directory named "public" found after the Build completed. You can configure the Output Directory in your Project Settings. Learn More: https://vercel.link/missing-public-directory

