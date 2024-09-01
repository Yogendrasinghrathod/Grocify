## How to SEtup tailwind css 
step1 : Run the following compound 

```
npm install-D tailwindcss 
npx tailwindcss init
```

step2 : Update tailwind.conf.js file to include this line 
```
content : ["*.html"],
```

step3 : create src/input.css  to include :

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

step4: Include the src/output.css file to your html

step 5: Run the following command

```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```