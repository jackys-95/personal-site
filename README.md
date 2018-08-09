# Personal Site
This is my personal website although it's not live yet and is very much a work-in-progress. The intent behind the design is an all-in-one showcase of who I am, what I'm thinking, and what I do. Read more about what went into the design on the website itself when it goes live!

Thanks to [Daniel Destefanis](https://github.com/destefanis) for allowing people to use his [website design](https://github.com/destefanis/new-portfolio) as a starting point. I have ported his website design into a Ruby project to take advantage of Jekyll and GitHub Pages. You may use my forked design and or extend it as you wish.

## Local Build
 If you want to poke around with Ruby and Jekyll, you can try a local build of my site. You should have Ruby 2.2.5 or above before starting. Use the following commands in a Bash *nix terminal.
 
```sh
cd $your-project-directory
gem install jekyll bundler
bundle exec jekyll serve
```

Go to a web browser and go to localhost:4000 (you can change the default port binding by using:

```sh
bundle exec jekyll serve -P port-number
```

Or by setting the port in \_config.yml.

## Features
I have added the following features to Daniel's original design with various roadmap annotations bracketed:

 * [Landing Page Blog Roll (IN-PROGRESS)](#Blog-Roll)
 * [Jekyll Blog Posts (NOT-STARTED)](#Jekyll-Blog)
 * [Project Showcase (IN-PROGRESS)](#Project-Summaries)
 * [Social Media Integration (BLOCKED)](#Social)
 * [Toggle Dark Mode (NOT-STARTED)](#Dark-Mode)
 * [Twitch.tv Showcase (UNDER-REVIEW)](#Twitch.tv-Showcase)


### Blog Roll
STATUS: IN-PROGRESS (Basic design completed, functionality to follow)

A blog roll is displayed on the landing page below the hero section.

The blog roll supports the following features:

 * Displays the latest three posts by default.
 * Single Page Application (SPA) style pagination via JavaScript.
 * Filters (SPA-style)
  * Most Popular (by social media metrics and number of comments).
  * Author's Choice Recommendation.
  * Keyword search (searches for keywords in Jekyll's post metadata).

### Jekyll Blog
STATUS: IN-PROGRESS (Designing layout)

Jekyll-based blog posts sporting a minimalist and responsive design. Posts are also cross-posted onto [Medium.com](https://medium.com) for increasing potential blog reach. Disqus provides a way for readers to engage with me via blog comments.

### Project Showcase
Status: IN-PROGRESS (Revising and implementing design)

When hovering over the landing page project showcase images, and expandable section  opens. These expandos provide a short summary of the project, and highlights the various technologies used.

### Social Media Integration
Status: BLOCKED (Requires blog and project post pages to be completed)
Social media sharing expandos allow for users to have the option to showcase my work/thoughts whilst not being too intrusive. These integrations connect with Facebook, Twitter, Reddit, and Hacker News and are implemented for the blog post and project pages.

Furthermore, any of the navigational links to various social media platforms incorporate their branding colours to allow for easier assocation.

### Toggle Dark Mode
STATUS: NOT-STARTED (waiting until the website is functional)
An alternate black theme for those browsing at night or those with OLED displays.

### Twitch Showcase
Status: UNDER-REVIEW (Not sure if I want to add this)

A page to advertise my Twitch stream.