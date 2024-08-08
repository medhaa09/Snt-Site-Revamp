##### Install with NPM 
`npm install`

**To start developing:**
##### Develop with NPM 
`npm run start`

**To generate the site HTML:**
##### Build with NPM 
`npm run build`

**npm run start** will run two commands parallel:  
`npx tailwindcss -i ./assets/css/main.css -o ./assets/css/style.css --watch`

Has paginated Categories and Tags. Markdown files will automatically convert images put into `/assets` folder to .webp images. 

## Image shortcodes for webp as well.
{{< imgc src="img-name.jpg" alt="Place alt text here." >}}
