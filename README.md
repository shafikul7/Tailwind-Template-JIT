# Tailwind-Template-JIT

 Tailwind Just-in-Time Mode
 
 
 Tailwind CSS v2.1 introduces a new just-in-time compiler for Tailwind CSS that generates your styles on-demand as you author your templates instead
 of generating everything in advance at initial build time.
 
 npx tailwindcss -o ./build/style.css
 
 npx tailwindcss -i ./src/style.css -o ./build/style.css --JIT --purge="./*.html" --watch
