# Bajrang Vastralay

A single-page website for **Bajrang Vastralay**, a family clothing store offering premium traditional and modern wear — sarees, kurtas, suiting, and kids collections.

The entire site is a self-contained static page (`index.html`) with inline CSS and JavaScript. No build step or dependencies required.

## Features

- Responsive design with a mobile nav toggle
- Sections: Hero, About, Collections, Why Shop With Us, Testimonials, and Contact
- Click-to-call, WhatsApp, and email contact links
- Contact form with client-side validation
- Scroll reveal animations and a back-to-top button
- Inline SVG favicon (no external asset)

## Project Structure

```
.
├── index.html      # The complete website (HTML + CSS + JS)
├── images/          # Image assets
└── README.md
```

## Running Locally

Open `index.html` directly in any browser, or serve it with a simple static server:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000/`.

## Deployment (Render Static Site)

This is a plain static site, so use these settings when creating a Static Site on Render:

| Field | Value |
| --- | --- |
| Branch | `main` |
| Root Directory | *(leave empty)* |
| Build Command | *(leave empty)* |
| Publish Directory | `.` |

> **Note:** The homepage file is `index.html`, which both Render and GitHub Pages serve as the default page automatically.

## Contact

- **Address:** Bajrang Vastralay, Station Road, Mohiuddin Nagar, 848114
- **Phone / WhatsApp:** +91 80833 02452
- **Email:** ajayvershashah@gmail.com
- **Hours:** Monday – Saturday | 9:00 AM – 9:00 PM
