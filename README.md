# Sri Madhura Tours & Travels

A static, host-ready editorial travel website.

## Run locally

Open `index.html` directly, or serve the project folder with any static server:

```bash
npx serve .
```

Then open the local URL shown by the server.

## Deploy

Use the project root (`Madhura Travels`) as the publish directory. No build command is required.

- **Netlify:** drag and drop the project folder, or connect the repository with build command empty and publish directory `.`.
- **Vercel:** import the project and choose the Other framework preset with no build command.
- **GitHub Pages:** publish the repository root from the Pages settings.
- **Any web server:** upload the complete folder and use `index.html` as the entry point.

The root entry point forwards to `Legacy/code.html`, where the page and its local `Assets` references live.
