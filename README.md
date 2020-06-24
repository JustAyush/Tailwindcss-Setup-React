# Create React App + Tailwindcss Setup

This is a basic setup for a react app with [tailwindcss][1] as a CSS framework. In addition to tailwindcss, the setup also contains:

- [postcss-import][2]: [A PostCSS][3] plugin that lets you organize stylesheets into different files. However, it is essential to know that unlike [Sass][4], it disallows ```@import``` statements anywhere except at the very top of a file.

- [Autoprefixer][5]: To add vendor-specific prefixes 

- [PurgeCSS][6]: A tool to strip out unused CSS classes. It is recommended to use PurgeCSS for production build only. It comes along with tailwindcss. So you don't have to install it separately.

Use the package manager npm to set up on your machine

```
npm install
npm start
```











[1]: https://tailwindcss.com/
[2]: https://github.com/postcss/postcss-import
[3]: https://github.com/postcss/postcss
[4]: https://sass-lang.com/
[5]: https://github.com/postcss/autoprefixer
[6]: https://github.com/FullHuman/purgecss
