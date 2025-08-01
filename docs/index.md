---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Safe VitePress"
  tagline: VitePress with FastAPI Authentication
  image:
    src: /logo.png
    alt: VitePress
  actions:
    - theme: brand
      text: Protected Markdown Examples
      link: /markdown-examples
    - theme: alt
      text: Protected API Examples
      link: /api-examples

features:
  - title: Secure Access
    details: Ensure that only authorized users can access your documentation with robust authentication mechanisms.
  - title: FastAPI Backend
    details: Robust authentication powered by FastAPI with secure JWT token handling and role-based access control.
  - title: Customizable Authentication
    details: Tailor the authentication process to fit your needs with customizable login pages and user management.

---