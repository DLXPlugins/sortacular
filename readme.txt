=== Sortacular - Instantly Sort and Organize WordPress Admin Menus Alphabetically ===

Contributors: ronalfy
Tags: admin menu, menu order, alphabetic, alphabetical, organize
Requires at least: 6.9
Tested up to: 7.0
Stable tag: 1.0.3
Requires PHP: 7.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Clean up your WordPress admin menus instantly by sorting menu items alphabetically. Sort menus like Settings and Tools, leaving Core items untouched.

== Description ==

Your WordPress admin menu gets messy fast. Plugins add their own items. Settings end up scattered. Finding what you need takes longer than it should.

<a href="https://dlxplugins.com/plugins/sortacular/">Sortacular</a> fixes this instantly.

It keeps the default WordPress menus exactly where you expect them, and neatly sorts everything added by plugins and themes alphabetically. This makes your admin menu easier to scan and much faster to use.

No setup. No settings.

Activate the plugin, and your menu is instantly organized.

A simple divider separates the default WordPress items from everything else, so you can clearly see what belongs to WordPress and what has been added by plugins or themes.

=== What gets organized ===

Sortacular keeps the main WordPress menus in their original order. Nothing moves or breaks.

Everything added by plugins and themes is grouped and sorted alphabetically.

This applies to:

* Settings
* Appearance
* Tools
* Dashboard

In multisite, it also works with:

* Settings
* Dashboard
* Themes

=== What changes after you install it ===

Instead of scrolling through a long, cluttered menu, you get a clean and predictable layout.

You will see:

* Core WordPress items at the top, unchanged
* A clear divider
* All plugin and theme items sorted from A to Z

This means you no longer have to guess where a plugin placed its settings and in what order. You can find things quickly, every time.

=== Who this is for ===

This plugin is especially useful if:

* You install a lot of plugins, and your admin menu feels crowded
* You manage client websites and need to move quickly
* You waste time clicking around trying to find settings
* You want a cleaner, more organized WordPress dashboard
* You like a sorting plugin, but want your Core items left alone

It is also helpful for beginners who feel overwhelmed by how messy the admin menu can become over time.

=== Why this matters ===

A messy admin menu slows you down.

When plugins add items in random places, it becomes harder to navigate your site. You spend more time searching and less time actually working.

By organizing everything into a clear structure, Sortacular makes your workflow faster and less frustrating.

It is a small change that makes a big difference, especially on sites with many plugins.

=== No configuration needed ===

There are no settings to manage.

You do not need to learn anything new or configure options.

Just activate the plugin, and your menus are automatically reorganized.

=== For developers ===

If you need more control, you can customize which items are treated as core using filters. Please check out <a href="https://github.com/DLXPlugins/sortacular">the Sortacular GitHub repo</a> for filters, examples, and ways you can help extend and contribute to the plugin.

There is also optional support for sorting top-level menus, but it's off by default.

This plugin has no admin options or settings, and it works automatically when activated.

== Frequently Asked Questions ==

= What parts of the admin menu does this organize? =

* **Settings**
* **Appearance**
* **Tools**
* **Dashboard**

In Multisite, the following menus are sorted:

* **Settings**
* **Dashboard**
* **Themes**

= Can this sort top-level menu items too? =

Yes, but it is optional.

By default, Sortacular organizes items only within menus. If you also want to sort top-level menu items, you can enable it with a small code snippet.


`
add_filter( 'sortacular_can_sort_top_level', '__return_true' );
`

= Do I need to set anything up? =

No.

Just activate the plugin, and your menus are automatically organized. There are no settings to manage.

= Will this work with all plugins? =

It works with most plugins that add items to the WordPress admin menu.

If you find something that is not sorted correctly, you can request support, and we can look into it. If you already have a plugin that sorts admin menus, it is not recommended to have both.

= Will this break my menu or change how WordPress works? =

No.

Sortacular does not remove or change any menu items. It only reorganizes them so they are easier to find.

= Can I turn it off or undo the changes? =

Yes.

Simply deactivate the plugin, and your menu will return to its original order.

= Does this affect performance? =

We've observed no noticeable impact. The sorting occurs only in the admin area and does not affect your site’s front end.

= Does this work with the Command Palette? =

It's complimentary. The command palette isn't always available.

= Will you be adding support for other top-level menus or third-party plugins? =

Sure. Please leave a feature request <a href="https://dlxplugins.com/support/">via my support form</a>.

== Installation ==

1. Search for 'Sortacular' when adding a plugin via the WordPress admin.
2. Activate Sortacular through the Plugins screen.

The Settings, Appearance, Tools, and Dashboard menus will update immediately.

== Screenshots ==

1. **Settings Menu** - Core items are shown first, with the rest shown alphabetically.
2. **Tools Menu** - Core items are shown first, with the rest shown alphabetically.
3. **Dashboard Mneu** - Core items are shown first, with the rest shown alphabetically.

== Changelog ==

= 1.0.3 =
* Released 2026-03-27
* Initial WordPress.org release.

= 1.0.2 =
* Released 2026-03-25
* Resolving CSS issues.

= 1.0.1 =
* Released 2026-03-16
* Sort top-level menu items too. Core menus remain untouched. The rest are sorted alphabetically.

= 1.0.0 =
* Released on 2026-03-14
* Sort Settings, Appearance, Tools, and Dashboard submenus with Core items first and a separator before alphabetically sorted items.
