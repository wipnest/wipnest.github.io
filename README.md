# wipnest.github.io

The WipNest landing page, privacy policy and terms, served by GitHub Pages at https://wipnest.github.io/.

- `index.html`, `privacy.html`, `terms.html`, `delete-data.html`, `style.css`: the site
- `test.html`: how to join closed testing on Google Play (group, opt-in, download)
- `assets/launch.mp4`: the launch video, re-encoded to 720p from the `vid/wipnest-launch` render
- `assets/`: images made from the brand art in the WipNest app repo (`design/brand/`)
- `fonts/`: Figtree, under the SIL Open Font License (`fonts/OFL.txt`)

Preview locally with `node tool/serve.mjs` and open http://localhost:4173. Pushing to `main` publishes.

The app links to `privacy.html` and `terms.html`, and Google Play and Google sign-in use them too, so keep those addresses stable.
