# Babanetworx Website

This is the official website for Babanetworx, a company that provides software solutions, data engineering services, and AI products.

## About

This website is built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). It showcases the company's services, expertise, and contact information.

## Local Development

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/) (version 2.5.0 or higher)
- [RubyGems](https://rubygems.org/pages/download)
- [Bundler](https://bundler.io/)

### Setup

1. Clone this repository:
   ```
   git clone https://github.com/babanetworx/babanetworx.github.io.git
   cd babanetworx.github.io
   ```

2. Install dependencies:
   ```
   bundle install
   ```

3. Run the site locally:
   ```
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

## Structure

- `_config.yml`: Configuration file for Jekyll
- `_layouts/`: Layout templates
- `_includes/`: Reusable components
- `assets/`: CSS, JavaScript, and images
- `services/`: Service pages
- `about.md`: About page
- `contact.md`: Contact page

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.