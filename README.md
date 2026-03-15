# My Personal Website

This is my personal website built with Hugo, a fast and flexible static site generator.

## About

This website serves as my personal portfolio, showcasing my professional experience, publications, and blog posts about my research and interests.

## Structure

- `content/`: Contains all the Markdown files for blog posts, publications, and other pages
- `layouts/`: Custom HTML templates for the website
- `static/`: Static files like images and PDFs
- `config.toml`: Main configuration file for the Hugo site

## How to Use

### Prerequisites

- [Hugo](https://gohugo.io/) (extended version recommended)
- Git

### Running Locally

1. Clone this repository:
   ```bash
   git clone git@github.com:amayuelas/my-website.git
   cd my-website
   ```

2. Install dependencies (if any):
   ```bash
   # Currently no external dependencies
   ```

3. Run the development server:
   ```bash
   hugo server -D
   ```

4. Open your browser to `http://localhost:1313`

### Building for Production

To generate the static files for deployment:
```bash
hugo
```

The generated files will be in the `public/` directory (which is ignored by Git).

## Deployment

This site is designed to be deployed as static files. You can deploy the contents of the `public/` directory to any static hosting service like:

- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any web server

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or issues, please open a GitHub issue or contact me directly.
