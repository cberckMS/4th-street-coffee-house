# 4th Street Coffee House — Website

A simple, warm & rustic single-page website for **4th Street Coffee House** in Stromsburg, NE.

## Project Structure

```
4th-street-coffee-house/
├── index.html        ← Main website (open in browser)
├── css/
│   └── style.css     ← Styles (warm rustic theme)
├── images/           ← Add your own photos here
└── README.md
```

## How to Preview

Just open `index.html` in your web browser — no build tools needed!

## How to Deploy to Azure Static Web Apps

1. **Create a GitHub repo** and push this folder to it
2. Go to the [Azure Portal](https://portal.azure.com)
3. Search for **Static Web Apps** → Create
4. Connect your GitHub repo
5. Set **App location** to `/` (root)
6. Leave build settings empty (no framework)
7. Deploy!

Azure will auto-deploy on every push to your repo.

## Customization

- **Photos:** Replace the placeholder in the About section and the hero background by adding images to the `images/` folder and updating the paths in `index.html` and `css/style.css`
- **Menu items & prices:** Edit the menu section in `index.html`
- **Hours:** Edit the hours table in `index.html`
- **Colors:** Tweak CSS variables at the top of `css/style.css`

## Custom Domain (Optional)

In Azure Static Web Apps settings → Custom Domains → add your domain (e.g., `4thstreetcoffeehouse.com`). Azure provides free SSL.
