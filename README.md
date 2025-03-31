# Automa website how-to

- Change content in /content/
  - Index page: content/_index.md
  - Newsletter page: content/newsletter/index.md

- Special cases under /layouts/
  - layouts/newsletter/single.html: the template for the newsletter page
  - layout/partials/subscribe.html: the copy-paste with the Mailchimp code
  - layout/partials/ other files (bio / footer / header): overrides of default layout of the theme

- Place static content under /static/  
d

- Github action to build the website: /.github/workflows/hugo.yaml