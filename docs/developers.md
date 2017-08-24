# Description

This page tells a bit about the development process.

##How would I reinstall the site?

Ask me at taipale.aleksi@gmail.com for the rights to the repository, and we'll continue from that.

##Wordpress:
The site is built on [Wordpress](http://wordpress.org/), and there are quite a few plugins in use alongside the vanilla WordPress installation

Most pages have their own custom php template, such as `page-home.php` and so forth.

###Wordpress plugins in use:

[Advanced Custom Fields Pro](https://www.advancedcustomfields.com/pro/)

The site will not work without this plugin, simple and plain. It is used in every custom post type and on every page.

---

[Akismet](https://wordpress.org/plugins/akismet/)

Spam filtering for the feedback form.

---

[All-in-one WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/)

This is great for importing/backuping the whole site locally when developing. At 24 August 2017 the install on the server is a multi-site install, for which this plugin does not work. However, I recommend this for backing up the site every now and then.

---

[Contact Form 7](https://wordpress.org/plugins/contact-form-7/)

Used for the feedback form at <http://onlinelearning.aalto.fi/feedback>.

---

[Disable Comments](https://wordpress.org/plugins/disable-comments/)

Disable all the comments on the page.

---

[Events Manager](https://wordpress.org/plugins/events-manager/)

Used extensively for the Events; i.e. changing the plugin used for events might require quite a lot of work. I don't recommend that.

---

[Post Types Order](https://wordpress.org/plugins/post-types-order/)

Used to allow the user to reorder posts.

---

[Regenerate Thumbnails](https://wordpress.org/plugins/regenerate-thumbnails/)

Handy tool for regenerating all thumbnails when you create new image sizes in f.ex. functions.php.

---

[Twitter](https://wordpress.org/plugins/twitter/)

Used for the Twitter feed embed.

---

##Theming:
Custom AOLE2017 theme, built on [FoundationPress](https://foundationpress.olefredrik.com/)

To modify the theme, you should get acquainted with the FoundationPress theme, since it is used throughout. The theme files are under `scss/custom/` as `_partialname.scss`-files. They are imported in the `foundation.scss` file. The partials should contain an explanation of what each file affects.
