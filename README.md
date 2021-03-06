# Development:
1. Clone repo (set up [GitHub SSH keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) first): `git clone git@github.com:zimmerry/stig-phantoms.git`
2. Initialize git submodule (upstream theme) [airspace-hugo](https://github.com/themefisher/airspace-hugo/tree/53fe1702638d934509b13c14f49ee613196deafc): `git submodule update --init --recursive`
3. Building and dev server: [Hugo 0.83.1](https://github.com/gohugoio/hugo/releases/tag/v0.83.1)
4. To run a dev server that updates as you make changes: Move into `stig-phantoms` directory and run `hugo server`. Access the server at `localhost:1313` or `127.0.0.1:1313`
5. To build static site from Hugo files: Move into `stig-phantoms` directory and run `hugo`

# Making changes:
1. Move into `stig-phantoms` directory
2. Checkout new git branch `git checkout -b <github username>/<changes>` For example: `git checkout -b zimmerry/add-calendar`
3. Implement changes
4. Commit changes with `git add .` and `git commit -m "<Changes implemented>"` For example: `git commit -m "Added STIG calendar"`
5. Push changes and make a pull request: `git push origin <username>/<changes>` For example: `git push origin zimmerry/add-calendar`
6. Request review from `zimmerry` on GitHub.
