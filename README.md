
# Bea’s Detroit WP Theme   

Production theme for Bea's Detroit. Relaunched in Summer 2021.


## Run Locally

Clone the project into themes directory of a local WordPress Installation. 

```bash
  git clone https://github.com/dropkick/beas-detroit-wp-theme.git
```

```bash
// gulp commands 

// $ gulp
exports.default = parallel(browserSync, watchFiles); 
// $ gulp sass
exports.sass = buildStyles; 
// $ gulp watch
exports.watch = watchFiles; 
// $ gulp build
exports.build = series(buildStyles); 

```

[Timber Starter Theme docs](https://timber.github.io/docs/).

## What's here?

`static/` is where you can keep your static front-end scripts, styles, or images. In other words, your Sass files, JS files, fonts, and SVGs would live here.

`templates/` contains all of your Twig templates. These pretty much correspond 1 to 1 with the PHP files that respond to the WordPress template hierarchy. At the end of each PHP template, you'll notice a `Timber::render()` function whose first parameter is the Twig file where that data (or `$context`) will be used. Just an FYI.

`bin/` and `tests/` ... basically don't worry about (or remove) these unless you know what they are and want to.


Development for this was done using [Local](https://getflywheel.com/design-and-wordpress-resources/toolbox/local-by-flywheel/) by Flywheel.

*Note: Previous versions of the site were developed using Fabrica Dev Kit running inside a Docker environment. So far, Local is a little more nimble and less problematic with relatively few hands in the project at a time.*
## Wordpress Plugin Dependencies

- [Timber](https://upstatement.com/timber)
- [Advanced Custom Fields](https://www.advancedcustomfields.com/)


## Additional Wordpress Plugins in use

- [Contact Form 7](https://contactform7.com/)
- [Disable Gutenberg](https://perishablepress.com/disable-gutenberg/)
- [Duplicate Page](https://wordpress.org/plugins/duplicate-page/)
- [Instagram Feed Pro Business](https://smashballoon.com/instagram-feed)
- [Post Types Order](http://www.nsp-code.com/)
- [Regenerate Thumbnails](https://alex.blog/wordpress-plugins/regenerate-thumbnails/)
- [Site Kit by Google](https://sitekit.withgoogle.com/) 
- [WP Migrate DB Pro](https://deliciousbrains.com/wp-migrate-db-pro/)
- [WP Migrate DB Pro Media Files](https://deliciousbrains.com/wp-migrate-db-pro/)
- [WP Migrate DB Pro Theme & Plugin Files](https://deliciousbrains.com/wp-migrate-db-pro/)
- [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/)

## Author

- Jason Duerr at [Dropkick Design](https://dropkick.design) in Portland Oregon USA - [@dropkick](https://www.github.com/dropkick) 


  
## Acknowledgements

 - [Unsold Studio](https://www.unsoldstudio.com/) - Graphic Design and UX

  