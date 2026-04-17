# Rayls Use Cases

A multi-page website showcasing the five core Rayls institutional blockchain use cases. Designed for deployment on Vercel.

## Pages

| Route | Description |
|-------|-------------|
| `/` | Redirects to the Use Cases Overview |
| `/pages/use-cases-overview` | Overview of all five use cases |
| `/pages/use-case-tokenised-deposits` | UC1: Tokenised Deposits |
| `/pages/use-case-yield-bearing-vaults` | UC2: Yield-Bearing Asset Vaults |
| `/pages/use-case-cross-border-payments` | UC3: Cross-Border Payments and FX |
| `/pages/use-case-private-trading` | UC4: Private Tokenised Asset Trading |
| `/pages/use-case-tokenised-treasury` | UC5: Tokenised Treasury Management |

## Deployment

### Vercel (recommended)

1. Push this repository to GitHub
2. Connect the repository to Vercel
3. Deploy with zero configuration (static site, no build step required)

### Vercel CLI

```bash
npx vercel --prod
```

### Netlify Drop

Drag and drop the entire `rayls-use-cases` folder into [Netlify Drop](https://app.netlify.com/drop).

## Navigation

- The overview page links to each individual use case via quick-nav cards and detailed section links
- Each individual use case page includes a breadcrumb back to the overview
- Each individual use case page includes a "Related Use Cases" section at the bottom linking to the other four use cases

## Brand

- Font: Rethink Sans (loaded via Google Fonts)
- Colours: #111111 (black), #ECFB3E (yellow), #B49AFF (purple), #EFF1F5 (grey)
- All pages are self-contained HTML with no build step required
