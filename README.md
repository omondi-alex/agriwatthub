# Agriwatt Hub Interactive Briefing

An interactive briefing document for partnering with Agriwatt Hub, featuring:
- Interactive navigation and smooth scrolling
- Tabbed content sections
- Data visualizations and charts
- Responsive design for all devices

## Local Development

```bash
# Start local server
python3 -m http.server 8000

# Or using npm
npm start
```

Then visit: http://localhost:8000/agriwatthub.html

## Deployment

This project is configured for easy deployment on Vercel:

1. Install Vercel CLI: `npm i -g vercel`
2. Deploy: `vercel`
3. Or connect your GitHub repository to Vercel for automatic deployments

The `vercel.json` configuration ensures the HTML file is served as the main page.

## Project Structure

- `agriwatthub.html` - Main interactive briefing document
- `vercel.json` - Vercel deployment configuration
- `package.json` - Project metadata and scripts
