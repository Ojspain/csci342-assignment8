Assignment 8

Oliver Spain (spaino, W01542192)

## Live URLs

- **Client:** https://platescout-yourname.vercel.app
- **Server:** https://platescout-yourname.onrender.com
- **Server health check:** https://platescout-yourname.onrender.com/api/health

## Local setup

1. Clone the repo
2. Copy `server/.env.example` to `server/.env` and fill in `MONGO_URI` + `JWT_SECRET`
3. From the root: `npm install` (client) and `cd server && npm install` (server)
4. Two terminals: `npm run dev` (root, client) + `npm run dev` (server)
5. Open http://localhost:5173

## What I learned during deployment

It was surprising how quickly you can spin something up directly from a repository. I have an interest in hosting my own projects, but I can see how these tools would be worth the cost to make deploying a significantly easier process. I found both of the dashboards a little overwhelming to try and understand immediatly, but with how much of the process is automated it was quick to pick up. I spent a while debugging why my Yelp API key stopped working. I figured out that it was because the API was originally being routed through the vite local proxy which wouldnt work on production. I will definitely plan future projects with these automated test and deployment pipeline features in mind because I can clearly see how much they speed up development.
