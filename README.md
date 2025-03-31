## Automa website how-to

- Change content in /content/
  - Index page: content/_index.md
  - Newsletter page: content/newsletter/index.md

- Special cases under /layouts/
  - layouts/newsletter/single.html: the template for the newsletter page
  - layout/partials/subscribe.html: the copy-paste with the Mailchimp code
  - layout/partials/ other files (bio / footer / header): overrides of default layout of the theme

- Place static content under /static/  
*E.g., if we want the /rr-youtoma/ website to work exactly as it does today, we only have to copy the entire contents of the current /rr-youtoma/ directory to static/rr-youtoma, and everything should work just fine.*

- Github action to build the website: /.github/workflows/hugo.yaml
