Oct 26, 2023

dev/pricewise

web-scraping project from tutorial:
    Web Scraping Full Course 2023 | Build and Deploy eCommerce Price Tracker
    https://www.youtube.com/watch?v=lh9XVGv6BHs

    by JavaScript Mastery

built with nextjs 13, brightdata, nodemailer, mongodb, cheerio, cron

start:
    npm run dev

deployment at Netlify:
    https://astonishing-licorice-19dbb7.netlify.app/

note about deployment: deployment at Vercel does not succeed because 
app/api/cron/route.ts line 9 'export const maxDuration = 10' is required by Vercel 
but 'export const maxDuration = 300'is needed for the app to work


there are accounts connected to this project at:
    cron-job.org
    brightdata.com
    mongodb.com

an outlook.com address (see .env) is used to receive pricing alerts


