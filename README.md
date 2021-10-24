# Development:
1. Building and dev server: [Hugo 0.83.1](https://github.com/gohugoio/hugo/releases/tag/v0.83.1)
2. To build static site from Hugo files: Move into `stig-phantoms` directory and run `hugo`
3. To run a dev server that updates as you make changes: Move into `stig-phantoms` directory and run `hugo server`. Access the server at `localhost:1313` or `127.0.0.1:1313`

# Making changes:
1. Move into `stig-phantoms` directory
2. Checkout new git branch `git checkout -b <github username>/<changes>` For example: `git checkout -b zimmerry/add-calendar`
3. Implement changes
4. Commit changes with `git add .` and `git commit -m "<Changes implemented>"` For example: `git commit -m "Added STIG calendar"`
5. Push changes and make a pull request: `git push origin <username>/<changes>` For example: `git push origin zimmerry/add-calendar`
6. Request review from `zimmerry` on GitHub.
