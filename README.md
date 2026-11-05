# Midland Lodge — landing site

One static page (`index.html`) for the Midland Lodge restoration in Sutton Park. No build step.

- **Hero:** a scroll-scrubbed film (today → restored → through the window → house tour). Upright phones load a vertical film; laptops and landscape screens load the widescreen one. All films are silent and hosted on Higgsfield's CDN.
- **Fonts:** Cormorant Garamond and Jost from Google Fonts.
- **Register interest form:** validates and thanks the visitor but does not send anywhere yet. See the `TODO` in the submit handler.

## Deploy

Import this repo into Vercel as a static site (framework preset: **Other**, no build command, output directory `.`).
