# Gemini3

A dynamic motion carousel with smooth drag interactions and responsive design.

## Features

- 🎨 Dark theme with modern UI
- 📱 Fully responsive design
- 🖱️ Drag and touch-enabled interactions
- ✨ Motion effects (blur, scale, brightness)
- 🎯 Smooth card snap-to-center navigation

## Project Structure

```
.
├── public/
│   └── index.html          # Main HTML file
├── package.json            # Project dependencies
├── vercel.json             # Vercel deployment config
├── .gitignore              # Git ignore rules
├── .vercelignore           # Vercel ignore rules
└── README.md               # This file
```

## Local Development

### Prerequisites

- Node.js 14+ (optional, for local server)
- Any modern web browser

### Installation & Running Locally

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Open your browser and navigate to:
```
http://localhost:3000
```

## Deployment

### Deploy to Vercel

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. Connect your repository to Vercel:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will auto-detect the configuration from `vercel.json`
   - Click "Deploy"

### Environment Variables

Currently, this project doesn't require environment variables. If you add features that do, add them via the Vercel Dashboard under Project Settings > Environment Variables.

## Customization

### Edit Carousel Data

Open `public/index.html` and locate the `filmData` array in the script section to customize the carousel items.

### Styling

CSS variables can be customized in the `:root` selector:

```css
:root {
    --card-width: 60vw;
    --card-height: 80vh;
    --gap-size: 2rem;
    --max-blur: 5px;
    --max-scale-reduction: 0.05;
}
```

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Tailwind CSS (CDN)

## License

MIT

## Support

For issues or questions, please create an issue in the repository.