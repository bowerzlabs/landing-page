# Coming Soon Landing Page

A sleek "Coming Soon" static landing page built with **HTML**, **Tailwind CSS**, and basic **JavaScript** countdown. Easily customizable via the `config` object.

---

## Features

- Countdown to launch
- Social links
- Email notify form (non-functional placeholder)
- Mobile responsive
- Minimalistic Tailwind styling
- Config-driven site content

---

## Configuration

Update the `config` object inside the `<script>` tag of `index.html` to match your brand:

```js
const config = {
  name: "SiteName",
  description: "We're working hard to launch our amazing website.",
  launchDate: "2025-12-31T00:00:00",
  socials: {
    x: "https://x.com/yourhandle",
    github: "https://github.com/yourusername",
    linkedIn: "https://linkedin.com/in/yourprofile"
  }
};
