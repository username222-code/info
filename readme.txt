Bible Lookup Website
Static KJV Bible lookup site for free deployment on Cloudflare Pages.
Deploy on Cloudflare Pages
    1. Push this folder to a GitHub repository.
    2. In Cloudflare, open Workers & Pages and create a Pages project from that repository.
    3. Set framework preset to None.
    4. Set build command to exit 0.
    5. Set build output directory to .
    6. Deploy.
Files
    • bible-lookup-tool.html — main site entry file
    • assets/kjv_seed.json — offline KJV dataset
Notes
For Cloudflare Pages, rename bible-lookup-tool.html to index.html before deployment, or copy it as index.html in the repo root.