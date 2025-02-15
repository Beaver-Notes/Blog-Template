# Blog-Template  

A static, privacy-focused blog inspired by [elementary's own blog](https://github.com/elementary/blog-template?tab=readme-ov-file).  

## Goals  

This is the third iteration of a blog that was originally written in Vue and then rewritten in Jekyll twice.  

- **Something that feels like home** – Reflecting the design language we have come to love in Beaver.  
- **Little to no JavaScript** – The less, the better. We tried to use as little JavaScript as possible.  
- **Hassle-free for the reader** – Easy to navigate and content-focused.  
- **RSS feed support** – For better cross-posting and reading experience.  
- **Reusable and scalable** – Something you can use for your project.  
- **Easy to maintain** – Writing articles is already time-consuming; why make it worse?  
- **Easy to deploy** – Compatible with GitHub Pages.  

## Repositories  

The blog is split into two repositories:  

1. [**Beaver-Blog**](https://github.com/Beaver-Notes/Beaver-Blog)  
2. [**Beaver-Blog-Template**](https://github.com/Beaver-Notes/Beaver-Blog-Template)  

The template follows Beaver's philosophy of making everything open source in a way that you can use in your own projects. The main repository holds a copy of the template plus the actual posts themselves and is set up with GitHub Pages.  

## Building & Running Locally  

The blog is a simple Jekyll-powered site hosted with GitHub Pages. To run it locally, see the [GitHub docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll).  

### To set up Jekyll and enable live reload during development:  

Install Jekyll and Bundler if not already installed:  

```bash
gem install jekyll bundler
```  

Install project dependencies:  

```bash
bundle install
```  

Run the Jekyll server with live reload enabled:  

```bash
bundle exec jekyll serve --livereload
```  

Access the development site at: [http://localhost:4000](http://localhost:4000)  

## Deployment 

To deploy the template using GitHub Pages, you can copy the workflow from the [Blog Repo](https://github.com/Beaver-Notes/Beaver-Blog/blob/main/.github/workflows/jekyll-gh-pages.yml) and refer to the [GitHub Docs](https://docs.github.com/en/actions/writing-workflows/using-workflow-templates) for detailed instructions.

## 💖 Contribution  

If you want to contribute to Beaver's own blog, check out our [docs](https://docs.beavernotes.com/beaver%20notes%20(dev)/2025/01/06/Contribute-to-blog.html). If you use this template in your project and want to improve it, feel free to open a pull request against this repo. Donations are, of course, always welcome.  