# Positivus

A responsive digital agency landing page built in WordPress with Elementor Free. This project recreates the supplied Positivus Figma design with editable Elementor sections and a custom companion plugin.

[View the live demo](https://positivus-world.netlify.app/)

## Features

- Responsive navigation with keyboard controls and a mobile menu
- Service cards with SVG arrows for consistent rendering across browsers
- Interactive process accordion and swipeable testimonials
- Editable team and footer sections, locally hosted fonts, and reduced-motion support
- Contact and newsletter forms for WordPress, with Netlify Forms configured separately in the static export

## Run locally

1. Set up a local WordPress installation and activate Elementor Free.
2. ZIP the [companion plugin folder](delivery/positivus-elementor-draft). Keep the folder itself as the top-level entry in the ZIP.
3. In WordPress, go to **Plugins → Add New Plugin → Upload Plugin**. Upload the ZIP and activate the plugin.
4. Go to **Tools → Positivus Import** and create the page draft. Open it in Elementor to edit or preview it.

The plugin folder contains the Elementor template, CSS, JavaScript, PHP form handlers, and the assets used by the page. The public demo is a static export hosted on Netlify. The editable version runs in WordPress.

## Testing

The local audit checked 1,601 viewport widths from 320 to 1,920 pixels for layout issues and ran interaction checks at 14 representative sizes. Chrome and WebKit tests covered navigation, SVG icons, testimonials, and the static export. Form delivery was mocked during automated tests.

## Credits

Based on the supplied Positivus Figma design and artwork. The bundled Space Grotesk font includes its license in the plugin's assets folder. Original design and artwork remain subject to their respective terms.
