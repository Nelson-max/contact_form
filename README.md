# Example of small contact form by using tailwindcss as a PostCSS Plugin


## Getting Started

1.  Clone the repository

         git clone https://github.com/Nelson-max/session_one.git {{ your project name }}

    Alternately you can download the zip file and unzip it.

2.  You will now have the cloned project folder. Open the project in
    Visual Studio Code editor (recommended code editor for Tailwind CSS
    Projects)

3.  Open new terminal within Visual Studio Code

4.  Download and install NPM (if asked)- [A Beginner’s Guide to npm](https://www.sitepoint.com/npm-guide/)

5.  Install dependencies (if asked)

        npm install

6.  Build using Tailwind CSS(if asked)

        npm run build

7.  Open the `public > index.html` file in your browser.

## How to use

-   Go to `public > index.html`start adding your own HTML.
-   If you need to add more HTML pages, add them in the `public` folder.
-   To extract classes and use the `@apply` directive, edit the custom CSS file in `src > styles.css`. Add any amount of custom CSS within this file. Refer [https://tailwindcss.com/docs/installation#using-a-custom-css-file](https://tailwindcss.com/docs/installation#using-a-custom-css-file)

Watch HTML files for changes and build automatically everytime using (if necessary)

    npm run watch

NOTE: Do NOT edit the file `public > dist > styles.css` directly - This is the distribution stylesheet. The CSS here is generated from `src > styles.css` using Tailwind when you build.

## Optimize for production

Before pushing your code (the `public` folder) for production, run the below command to reduce the size of `styles.css` within the public folder

     npm run prod

NOTE: If you are using Windows and face an error `NODE ENV not recognised`, run the below command

     npm install win-node-env
