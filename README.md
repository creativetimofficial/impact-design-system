# [Impact Design System](https://demos.creative-tim.com/impact-design-system/index.html) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/share?url=http%3A%2F%2Fdemos.creative-tim.com%2Fimpact-design-system%2Findex.html&text=Kick-Start%20Your%20Development%20With%20Impact%20Design%20System&via=creativetim%20%40themesberg&hashtags=bootstrap%20%23designsystem%20%23opensource)

 ![version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/impact-design-system.svg?maxAge=2592000)](https://github.com/creativetimofficial/impact-design-system/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/impact-design-system.svg?maxAge=2592000)](https://github.com/creativetimofficial/impact-design-system/issues?q=is%3Aissue+is%3Aclosed) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)

![Impact Design System Thumbnail](https://s3.amazonaws.com/creativetim_bucket/products/296/original/opt_impact_thumbnail.jpg)

Kick-Start Your Development With An **Awesome Design System** carefully designed for your online business showcase. It comes as a complete solution, with front pages and dashboard pages included. 

**Impact Design System** features a huge number of components built to fit together and look amazing. If you are a new business looking to create your online presence or you just want to let people know who you are and what you do, this might be the answer for you.

### Fully Coded Components

Impact Design System features **over 200 individual components**, giving you the freedom of choosing and combining. This means that there are thousands of possible combinations. All components can take variations in color, that you can easily modify using SASS files.

You will save a lot of time going from prototyping to **full-functional code** because all elements are implemented. We wanted the design process to be seamless, so switching from image to the real page is very easy to do.

View all components [here](https://demos.creative-tim.com/impact-design-system-pro/docs/dashboard/alerts/).

### Example Pages

If you want to get inspiration or just show something directly to your clients, you can jump-start your development with our pre-built example pages. From **landing pages** to **e-commerce** or **blog pages**, you will be able to quickly set up the basic structure for your web project.

View example front pages [here](https://demos.creative-tim.com/impact-design-system/front/pages/index.html) and example dashboard pages [here](https://demos.creative-tim.com/impact-design-system/dashboard/pages/dashboards/dashboard.html).

### Complex Documentation

Each element is well presented in very complex documentation. You can read more about the idea behind this design system [here](https://demos.creative-tim.com/impact-design-system-pro/docs/getting-started/overview/). You can check the components [here](https://demos.creative-tim.com/impact-design-system-pro/docs/dashboard/alerts/).

## Table of Contents

* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Demo

| Landing | About | Pricing | Contact |
| --- | --- | --- | --- |
| [![Landing Page](https://demos.creative-tim.com/impact-design-system/front/assets/img/pages/github/landing.jpg)](https://demos.creative-tim.com/impact-design-system/front/pages/index.html) | [![About Page](https://demos.creative-tim.com/impact-design-system/front/assets/img/pages/github/about.jpg)](https://demos.creative-tim.com/impact-design-system/front/pages/about.html) | [![Pricing page](https://demos.creative-tim.com/impact-design-system/front/assets/img/pages/github/pricing.jpg)](https://demos.creative-tim.com/impact-design-system/front/pages/pricing.html) | [![Contact Page](https://demos.creative-tim.com/impact-design-system/front/assets/img/pages/github/contact.jpg)](https://demos.creative-tim.com/impact-design-system/front/pages/contact.html)

| Dashboard | Login | Profile | Documentation |
| --- | --- | --- | --- |
| [![Dashboard](https://demos.creative-tim.com/impact-design-system/front/assets/img/pages/github/dashboard.jpg)](https://demos.creative-tim.com/impact-design-system/dashboard/pages/dashboards/dashboard.html) | [![Login](https://demos.creative-tim.com/impact-design-system/front/assets/img/pages/github/dblogin.jpg)](https://demos.creative-tim.com/impact-design-system/dashboard/pages/examples/login.html) | [![Profile](https://demos.creative-tim.com/impact-design-system/front/assets/img/pages/github/dbprofile.jpg)](https://demos.creative-tim.com/impact-design-system/dashboard/pages/examples/profile.html) | [![Documentation](https://demos.creative-tim.com/impact-design-system/front/assets/img/pages/github/docs.jpg)](https://demos.creative-tim.com/impact-design-system-pro/docs/getting-started/overview/) 

[View More](https://demos.creative-tim.com/impact-design-system/)

## Quick start

1. Clone this repository or download from [Creative Tim](https://www.creative-tim.com/product/impact-design-system)
2. Make sure you have Node locally installed.
3. Download Gulp Command Line Interface to be able to use gulp in your Terminal.

```
npm install gulp-cli -g
```

4. After installing Gulp, run npm install in the main `impact-design-system-vx.x.x/` folder to download all the project dependencies. You'll find them in the `node_modules/` folder.

```
npm install
```

5. Run gulp in the `impact-design-system-vx.x.x/` folder to serve the project files using BrowserSync. Running gulp will compile the theme and open `/index.html` in your main browser.

```
gulp
```

While the gulp command is running, files in the `assets/scss/`, `assets/js/` and `components/` folders will be monitored for changes. Files from the `assets/scss/` folder will generate injected CSS.

Hit `CTRL+C` to terminate the gulp command. This will stop the local server from running.

### Theme without Sass, Gulp or Npm

If you'd like to get a version of our theme without Sass, Gulp or Npm, we've got you covered. Run the following command:

```
gulp build:dev
```

This will generate a folder `html&css` which will have unminified CSS, Html and Javascript.

### Minified version

If you'd like to compile the code and get a minified version of the HTML and CSS just run the following Gulp command:

```
gulp build:dist
```

This will generate a folder `dist` which will have minified CSS, Html and Javascript.

## Documentation
The documentation for Impact Design System is hosted at our [website](https://demos.creative-tim.com/impact-design-system-pro/docs/getting-started/overview/).


## File Structure
Within the download you'll find the following directories and files:

```
.
├── LICENSE.md
├── README.md
├── dashboard
│   └── assets
├── gulpfile.js
├── package-lock.json
├── package.json
└── src
    ├── dashboard
    │   ├── assets
    │   │   ├── fonts
    │   │   ├── img
    │   │   └── js
    │   ├── pages
    │   │   ├── dashboards
    │   │   ├── examples
    │   │   ├── maps
    │   │   └── tables
    │   ├── partials
    │   │   ├── _head.html
    │   │   ├── _tracking-body.html
    │   │   └── _tracking.html
    │   └── scss
    │       ├── bootstrap
    │       ├── core
    │       ├── custom
    │       └── dashboard.scss
    ├── front
    │   ├── assets
    │   │   ├── img
    │   │   └── js
    │   ├── pages
    │   │   ├── about.html
    │   │   ├── all.html
    │   │   ├── contact.html
    │   │   ├── index.html
    │   │   └── pricing.html
    │   ├── partials
    │   │   ├── _demo.html
    │   │   ├── _footer.html
    │   │   ├── _head.html
    │   │   ├── _navigation.html
    │   │   ├── _preloader.html
    │   │   ├── _pricing.html
    │   │   ├── _scripts.html
    │   │   ├── _tracking-body.html
    │   │   ├── _tracking.html
    │   │   └── cta
    │   └── scss
    │       ├── bootstrap
    │       ├── front
    │       └── front.scss
    └── index.html
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/chrome-logo.png?raw=true" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/firefox-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/edge-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/safari-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/opera-logo.png" width="64" height="64">

## Resources
- Demo: <https://demos.creative-tim.com/impact-design-system/index.html>
- Download Page: <https://www.creative-tim.com/product/impact-design-system>
- Documentation: <https://demos.creative-tim.com/impact-design-system-pro/docs/getting-started/overview>
- License Agreement: MIT License
- Support: <https://www.creative-tim.com/contact-us>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/impact-design-system/issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Impact Design System. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Impact Design System. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/?ref=mk-github-readme).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Licensing

- Copyright 2020 Creative Tim (https://www.creative-tim.com/?ref=mk-github-readme)
- Licensed under MIT (https://github.com/creativetimofficial/impact-design-system/blob/master/LICENSE.md)

## Useful Links Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)
- [Affiliate Program](https://www.creative-tim.com/affiliates/new?ref=mk-github-readme) (earn money)
- [Blog Creative Tim](http://blog.creative-tim.com/)
- [Free Products](https://www.creative-tim.com/bootstrap-themes/free?ref=mk-github-readme) from Creative Tim
- [Premium Products](https://www.creative-tim.com/bootstrap-themes/premium?ref=mk-github-readme) from Creative Tim
- [React Products](https://www.creative-tim.com/bootstrap-themes/react-themes?ref=mk-github-readme) from Creative Tim
- [Angular Products](https://www.creative-tim.com/bootstrap-themes/angular-themes?ref=mk-github-readme) from Creative Tim
- [VueJS Products](https://www.creative-tim.com/bootstrap-themes/vuejs-themes?ref=mk-github-readme) from Creative Tim
- [More products](https://www.creative-tim.com/bootstrap-themes?ref=mk-github-readme) from Creative Tim
- Check our Bundles [here](https://www.creative-tim.com/bundles?ref=mk-github-readme)

### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Instagram: <https://www.instagram.com/CreativeTimOfficial>

## Useful Links Themesberg

- [Free themes](https://themesberg.com/products/free-themes) from Themesberg
- [Premium themes](https://themesberg.com/products/premium-themes) from Themesberg
- [Blog Themesberg](https://themesberg.com/blog) from Themesberg

### Social Media

- [Follow @themesberg](https://twitter.com/themesberg) on Twitter
- [Like Themesberg](https://www.facebook.com/themesberg/) on Facebook
- [Follow Themesberg](https://dribbble.com/themesberg) on Dribbble
- [Follow Tthemesberg](https://www.instagram.com/themesberg/) on Instagram
