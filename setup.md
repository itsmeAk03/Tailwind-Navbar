## How to setup Tailwind CSS

Step 1: Run following commands in terminal

```
npm install -D tailwindcss
npx tailwindcss init
```
ek file banke aaega tailwind.conf.js 

Step 2: Update the tailwind.conf.js file to include this line :

```
content: ["*.html"],
```
Step 3: Create a folder "src" inside it create a file "input.css"

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
ek output.css file banjaaega src mei 

Step 4:Include the src/output.css file to your html

Step 5: run the following command 

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
