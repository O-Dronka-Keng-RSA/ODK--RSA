# O DRONKA KENG? RSA

High-end brutalist streetwear designed in Pretoria, Gauteng (012).

## Overview
O Dronka Keng? RSA is a South African streetwear brand that combines brutalist design with high-end fashion. Our website showcases our latest collection, "Day Zero," and provides information about our brand and mission.

> O Dronka Keng? isn't a question of substance; it's a question of spirit. In the streets of RSA, we don't just walk; we hustle. We aren't just dressed; we're armored. Whether it’s the 'Day Zero' grind or the 'Poison' of ambition—what are you drunk on?

           
* **Manifesto**: Learn about our brand's philosophy and values
* **Vault**: Explore our latest collection, "Day Zero"
* **Contact**: Get in touch with us to join the Syndicate or inquire about products

## About Us
O Dronka Keng? RSA is based in Pretoria, South Africa. We're part of the Pretoria Syndicate, pushing boundaries in streetwear and design.

                  
* Facebook:https://www.facebook.com/ODronkaKengFam/                     
* Email: odronkakengfam@gmail.com 

             
* HTML5
* CSS3 (with brutalist-inspired styling)
* JavaScript (for interactive elements)

                    
Our design is inspired by brutalist architecture and South African street culture. We aim to create clothing that's both functional and thought-provoking.

## Collections
* **Day Zero**: Our latest collection, now live in the Vault

## Contributing
Want to join the Syndicate? Reach out to us via the contact form on our website.

## License
All content on this website is property of ODK-RSA. Unauthorized use is prohibited.

---

## Publishing as a GitHub Pages Site

To host this site at `https://O-Dronka-Keng-RSA.github.io`, the repository must be
named exactly `O-Dronka-Keng-RSA.github.io` and belong to the `O-Dronka-Keng-RSA`
account (user or organization).

1. **Create or rename** a GitHub repository with that name (via the web UI or
   `gh repo create`).
2. **Push the workspace contents** to the new repo, for example:
   ```bash
   git remote set-url origin \
     https://github.com/O-Dronka-Keng-RSA/O-Dronka-Keng-RSA.github.io.git
   git checkout Master
   git push origin Master:main
   ```
3. The included workflow (`.github/workflows/pages.yml`) deploys the files on
   every push to `Master`.
4. Enable Pages in the repository settings (branch `main`/`Master`, root). The
   site will appear shortly at the user URL.

(Optional) Add a `CNAME` file or configure a custom domain for branding.

### Project site alternative

If you prefer to keep using the existing
`ODK--RSA` repository name, the workflow is already configured to publish to
the `gh-pages` branch. In this case the Pages site will be available at:

```
https://O-Dronka-Keng-RSA.github.io/ODK--RSA/
```

The steps are simply:

1. Push the current `Master` branch (or any branch you like) to GitHub. The
   workflow will automatically update the `gh-pages` branch with the contents
   of the repo.
2. In **Settings → Pages** set the source to **gh-pages branch** (root). GitHub
   will serve from that branch and the site URL above will become active.
3. Future pushes to `Master` will automatically redeploy via the GitHub Action.

This approach avoids having to rename or create a new repository, but the URL
includes the repository name.

