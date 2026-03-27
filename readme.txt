=== Sortacular - Sort Select Admin Settings ===

Contributors: ronalfy
Tags: admin, menu, settings, sort, organize
Requires at least: 6.9
Tested up to: 7.0
Stable tag: 1.0.3
Requires PHP: 7.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Keep WordPress Core menu items organized and sort items alphabetically in Settings, Appearance, Tools, and Dashboard. Leaves Core menu items alone.

== Description ==

Sortacular organizes your WordPress admin sidebar so it's easier to find what you need. Core menu items (the ones that ship with WordPress) stay at the top in their normal order. A small divider separates them from plugin and theme items, which are then sorted A–Z.

This plugin has no admin options or settings, and it works automatically when activated.

=== What Sortacular Sorts ===

* **Settings** – General, Writing, Reading, and other Core settings stay first; third-party options follow, alphabetically.
* **Appearance** – Themes, Editor, Menus, and other Core items stay first; theme/plugin items follow, alphabetically.
* **Tools** – Available Tools, Import, Export, Site Health, and other Core items stay first; plugin tools follow, alphabetically.
* **Dashboard** – Core items stay first; any added items follow, alphabetically.

In Multisite, the following menus are sorted:

* ** Settings **
* ** Dashboard **
* ** Themes **

=== Configuration ===

No configuration needed. Activate the plugin and the menus are reorganized automatically. You can customize which items count as "Core" using the provided filters if you need to.

== Frequently Asked Questions ==

= What menus are sorted automatically? =

* **Settings**
* **Appearance**
* **Tools**
* **Dashboard**

In Multisite, the following menus are sorted:

* ** Settings **
* ** Dashboard **
* ** Themes **

= Do you support sorting top-level menus? =

Yes, add this to your site's code. The sorting for top-levels is still experimental and seeking feedback, which is why it is opt-in.

`
add_filter( 'sortacular_can_sort_top_level', '__return_true' );
`

= Do you have admin settings or anything to configure? =

Not at all. The sorting is applied automatically and there are no admin settings.

= Will you be adding support for other top-level menus or third-party plugins? =

Sure. Please leave a feature request <a href="https://dlxplugins.com/support/">via my support form</a>.


== Installation ==

1. Upload the plugin folder to `/wp-content/plugins/` or install via the Plugins screen.
2. Activate Sortacular through the Plugins screen.

The Settings, Appearance, Tools, and Dashboard menus will update immediately.

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
