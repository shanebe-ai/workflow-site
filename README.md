# workflowsetup.ca

Landing page for the AI workflow setup service: one workflow, two weeks, $2,500 flat.

## What's here

Single static page, `index.html`. No build step, no framework.

## Preview locally

Open `index.html` in a browser.

## Deploy

Server 1 (37.27.80.77) serves this repo straight from `/home/workflowsetup` through nginx, with SSL from certbot. A root cron job runs `git pull` every minute, so a push to main goes live within a minute.

## Config

- Booking link: Google Calendar appointment page, used in the three "Book a call" buttons
- Contact email: footer
