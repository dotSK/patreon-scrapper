# patreon-scraper
WIP Patreon attachment download written in TypeScript

# Description
Very WIP Patreon attachment downloader. Currently tries to download all attachments to out/ folder, skipping files that exist (checks filename).

Written in TypeScript because I like it. Hopefully will get better in future.

# Requirements
- NodeJS
- npm

# Installation
- Clone repo
- `npm install`

# Running
- Insert your current sessionId from Patreon cookie into index.ts
- `npm run app`

# TODO
- [ ] Choose Your Own Download Folder™
- [ ] Accept sessionId as argument/environment variable
- [ ] Download speed/stats?
- [ ] Better auth/connection checking
- [ ] Use selenium/webdriver to log in?
