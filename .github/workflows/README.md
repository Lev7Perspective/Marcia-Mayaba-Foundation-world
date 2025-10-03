# Marcia Mayaba Foundation Website

![Marcia Mayaba Foundation](./public/foundation-logo.svg)

The official website for the Marcia Mayaba Foundation - Empowering girls and women from township schools to the automotive boardroom.

## About the Foundation

The Marcia Mayaba Foundation exists to honor legacy through action by creating opportunities for the girl child from early development to adulthood, and opening pathways into education and industries, in particular the automotive sector.

Guided by **grace, dignity, and strength**, we empower girls and women to break barriers and achieve their full potential in traditionally male-dominated industries.

## Features

- 🎨 Modern, responsive design
- ⚡ Built with Next.js 14 and TypeScript
- 🎯 Optimized for performance and SEO
- 📱 Mobile-first approach
- 🌟 Smooth animations and interactions
- 📧 Contact form with toast notifications
- 🎨 Beautiful UI components with Tailwind CSS

## Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Custom components with Radix UI primitives
- **Icons**: Lucide React
- **Deployment**: GitHub Pages

## Getting Started

### Prerequisites

- Node.js 18 or later
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/marcia-mayaba-foundation.git
cd marcia-mayaba-foundation
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Building for Production

To create a production build:

```bash
npm run build
```

To export the static site for GitHub Pages:

```bash
npm run export
```

## Deployment

This website is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup Instructions

1. **Create a GitHub Repository**:
   - Create a new repository on GitHub
   - Name it `marcia-mayaba-foundation` or your preferred name

2. **Update Configuration**:
   - Update the `repository` field in `package.json`
   - Update the `homepage` field in `package.json`
   - Update the `basePath` in `next.config.js` if needed

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to the "Pages" section
   - Set source to "GitHub Actions"

4. **Push your code**:
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/marcia-mayaba-foundation.git
   git push -u origin main
   ```

5. **Automatic Deployment**:
   - The GitHub Action will automatically build and deploy your site
   - Your site will be available at `https://yourusername.github.io/marcia-mayaba-foundation`

## Customization

### Logo and Branding

- Replace `/public/foundation-logo.svg` with your actual foundation logo
- Update the colors in `tailwind.config.js` to match your brand
- Modify the primary color scheme in `app/globals.css`

### Content

- Update the content in `app/page.tsx` to reflect your organization's information
- Modify contact information and social media links
- Update the programs and impact sections with your specific data

### Styling

- The design uses a custom color palette based on the foundation's branding
- Modify colors in `tailwind.config.js` and `app/globals.css`
- Update typography and spacing as needed

## Project Structure

```
├── app/
│   ├── globals.css         # Global styles
│   ├── layout.tsx          # Root layout
│   └── page.tsx           # Main page component
├── components/
│   └── ui/                # Reusable UI components
├── hooks/                 # Custom React hooks
├── lib/                   # Utility functions
├── public/                # Static assets
├── .github/
│   └── workflows/         # GitHub Actions
└── README.md
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## Support

For support or questions about the website, please contact:

- **Email**: marciamayabafoundation@gmail.com
- **Website**: [Foundation Website](https://yourusername.github.io/marcia-mayaba-foundation)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with ❤️ by Leverage Inc
- Images from Unsplash
- Icons by Lucide React
- UI components inspired by shadcn/ui

---

**Marcia Mayaba Foundation** - Empowering girls and women from township schools to the automotive boardroom.

