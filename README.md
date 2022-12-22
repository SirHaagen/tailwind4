# Tailwind with npm

**1. npm init**
**2. npm install -D tailwindcss**
**3. Add the input style.css with Tailwind directives**
```javascript
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```
**4. Add the proper content in tailwind.config.js, for example:**
```javascript
  content: [
    './**/*.{html,js}'
  ]
```
**5. Add the link:css to index.html**
**6. npm tailwindcss -i inputCSS -o outputCSS --watch (run this line to compile a CSS output file**
**7. Run the Live Server**
