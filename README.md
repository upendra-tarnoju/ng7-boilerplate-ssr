# Angular 7 Boilerplate Universal app - Server Side Rendering


**Steps to Follow**

 1. npm install
 2. npm run build:ssr && npm run serve:ssr
 

**For Production**
  1. npm run build:ssr
  2. copy dist/ folder to your server
  3. navigate to folder where dist/ folder exist in your server
  4. npm install -g pm2 --> Install *pm2*
  5. pm2 dist/server.js  --> Which runs on port *4000*
  6. Use nginx reverse proxy to running port *(OR)* run pm2 to 80 port
  
 