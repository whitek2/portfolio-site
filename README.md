# hugo-starter

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/allegheny-college-junior-innovators/hugo-starter)

This template uses [Netlify](https://www.netlify.com/), [Hugo](https://gohugo.io/), and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) Hugo theme. You can use the button above to instantly create a new repository based off of this one, and deploy it to Netlify for free.

The following values should be configured or removed in your deployed instance of this template.

In `config.toml`:

- The `baseURL` key, to match what your chosen URL is on Netlify.
- The `title` key, to configure what your website is titled (and thus what the browser tab is named).
- Entries in the `[params]` table, to configure the `author`, `description`, `keywords`, and various other theme options.
- Entries in the `[params.label]` table, to configure the home label in the top-left corner.
- Entries in the `[params.profileMode]` table, to configure what you'd like to display on the main page.
- Entries in the `[params.profileMode.buttons]` array of tables, to configure what buttons you'd like on the main page. You can also remove the existing entries to have no buttons.
- Entries in the `[params.socialIcons]` array of tables, to configure what social icons and links are on the main page.
- Entries in the `[menu.main]` array of tables, to configure the top navigation links.

In `static/`:

- `profile.png`, to configure the image to show on the main page (or, if you'd like no image, remove the `image`-related keys in the `[params.profileMode]` table in `config.toml`)
- Any other static assets like images, fonts, or other static files and folders that you might want to link, reference, or use in your website. These will be available under the root directory of your website -- so, `profile.png` can be directly linked to with `/profile.png`.

In `contents/`:

- The contents (and existence) of the `blog/` folder, if you'd like to have blog posts on your website.
- The contents of the `projects/` folder -- either edit `_index.md` to show your project details all on one page, or create a project file for each ( use `hugo new --kind project projects/<name-of-project>`), which will be displayed as a card on the projects page.
- Any additional folders and/or files you'd like; each can be linked to by their file path, so `content/test-folder/my-page.md` would be accessed on your website as `/test-folder/my-page`, and you can add links to them in other pages or the top navigation menu.

Experimentation and creativity in organizing and creating content for your website is very important! If you are confused or would like to find out more about the possible configuration options of the PaperMod theme, visit the [demo website](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-features/), which lists many of the available configuration options not used in this template.

If the PaperMod theme isn't quite to your liking, you can easily remove it (use `git rm themes/PaperMod`) and use a different theme! There are many to choose from; [themes.gohugo.io](https://themes.gohugo.io/) contains hundreds of options. Below are a few options and the command you could use to add that theme (after removing PaperMod).

- [Gokarna](https://github.com/526avijitgupta/gokarna) - `git submodule add https://github.com/526avijitgupta/gokarna.git themes/gokarna` - [Setup Guide](https://gokarna-hugo.netlify.app/posts/theme-documentation-basics/)
- [Developer Portfolio](https://github.com/samrobbins85/hugo-developer-portfolio) - `git submodule add https://github.com/samrobbins85/hugo-developer-portfolio themes/hugo-developer-portfolio`
- [Highlights](https://github.com/schmanat/hugo-highlights-theme) - `git submodule add https://github.com/schmanat/hugo-highlights-theme.git themes/hugo-highlights-theme`
- [Osprey Delight](https://github.com/kdevo/osprey-delight) - `git submodule add https://github.com/kdevo/osprey-delight.git themes/osprey-delight`

Keep in mind that every theme is different, and you will need to read through the documentation to discover what entries you can add to `config.toml` and what content structure you should have in `content/`.
