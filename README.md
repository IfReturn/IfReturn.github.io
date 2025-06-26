# IfReturn.github.io

This is my personal blog hosted on GitHub Pages, built with Jekyll.

## 🚀 Quick Start

### Local Development

1. Install Ruby and Bundler
2. Clone this repository
3. Install dependencies:
   ```bash
   bundle install
   ```
4. Run the site locally:
   ```bash
   bundle exec jekyll serve
   ```
5. Open http://localhost:4000 in your browser

### Writing Posts

1. Create a new file in `_posts/` directory
2. Name it following the pattern: `YYYY-MM-DD-title.md`
3. Add front matter at the top:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS +TIMEZONE
   categories: category
   tags: [tag1, tag2]
   ---
   ```
4. Write your content in Markdown

## 📝 Site Structure

```
├── _config.yml          # Site configuration
├── _posts/              # Blog posts
├── _layouts/            # Custom layouts (optional)
├── _includes/           # Reusable components (optional)
├── _sass/               # Custom styles (optional)
├── assets/              # Images, CSS, JS files
├── index.md             # Homepage
├── about.md             # About page
└── Gemfile              # Ruby dependencies
```

## 🎨 Customization

This site uses the Minima theme. You can customize it by:
- Editing `_config.yml` for site settings
- Adding custom CSS in `assets/css/style.scss`
- Creating custom layouts in `_layouts/`
- Adding custom includes in `_includes/`

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions when you push to the `main` branch.

## 📄 License

This blog content is licensed under [MIT License](LICENSE).

## 📞 Contact

- GitHub: [@IfReturn](https://github.com/IfReturn)
- Email: yzc2004.12@qq.com

---

Built with ❤️ using Jekyll and GitHub Pages
