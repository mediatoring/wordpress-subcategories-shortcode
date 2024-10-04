# Show Subcategories Shortcode Plugin

## Description

The **Show Subcategories Shortcode** is a WordPress plugin developed by Webklient.cz that allows you to display subcategories of the current category on a category page using a simple shortcode. This plugin is designed to improve navigation and user experience by displaying a structured list of subcategories.

## Features

- Easily display subcategories of the current category.
- Customizable output with unique CSS classes for easy styling.
- Shortcode-based solution for seamless integration.
- Backend help page for easy guidance.

## Installation

1. Upload the `show-subcategories-shortcode` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the **Plugins** menu in WordPress.
3. Use the `[show_subcategories]` shortcode on your category pages to display the subcategories.

## Usage

To use this plugin, simply add the following shortcode to your category pages:

```
[show_subcategories]
```

When the shortcode is used, the plugin will display a list of all subcategories of the current category, wrapped in well-structured HTML with unique CSS classes for easy customization.

## Customizing the Styles

The output of the shortcode is wrapped in the following CSS classes to make styling easy:

- `.show-subcategories-container`: The main container wrapping the entire subcategory list.
- `.show-subcategories-menu`: The container wrapping the menu navigation.
- `.show-subcategories-nav`: The `<nav>` element wrapping the list of subcategories.
- `.show-subcategories-list`: The `<ul>` element containing all the subcategory items.
- `.show-subcategories-item`: The `<li>` element for each subcategory.

You can add your custom styles in your theme's stylesheet or use a custom CSS plugin to style these elements to match your website's design.

## Help and Support

A help page is available in the WordPress admin under **Appearance > Subcategories Shortcode**. This page contains details about the plugin, how to use the shortcode, and examples for customization.

## License

This plugin is licensed under the GPL-2.0+ License. You are free to use, modify, and distribute it under the terms of this license.

## Changelog

### Version 1.0.0
- Initial release of Show Subcategories Shortcode Plugin.

