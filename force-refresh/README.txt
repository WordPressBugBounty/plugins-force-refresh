=== Force Refresh ===
Stable tag: 2.17.0
Contributors: jordanleven
Tags: refresh, reload, single page application
Requires PHP: 8.2
Requires at least: 6.3
Tested up to: 6.9
License: GPLv2 or later
Force Refresh is a simple plugin that allows you to force a page refresh for users currently visiting your site on a per-page or post basis.


== Description ==
Force Refresh is the best plugin for requesting browsers to refresh their page. Perfect for single-page applications or pages that bring in feeds, this simple plugin will allow you to force a page refresh for users currently visiting any page of your site.

== Features ==
- Support for both parent and child themes.
- Allows an admin to simply click a button to request browsers to refresh their page. This is done within your selected customized client-side refresh interval.
- Ability to add refreshing capabilities to any role using the "Invoke Force Refresh" capability.
- Ability to refresh on a per-page or post basis.
- Customizable client-side refresh intervals, including the ability to customize any refresh interval between 30 seconds and four hours.

== Feature Requests and Bug Reports ==
- Please report any bugs you encounter [under the Support tab](https://wordpress.org/support/plugin/force-refresh).
- Feature requests can be made [on GitHub](https://github.com/jordanleven/force-refresh/issues). Force Refresh is an open-source plugin, and PRs are welcomed!

== Installation ==
Upload the Force Refresh plugin to your site, and then simply activate it. To force a refresh, just navigate to "Tools", click on "Force Refresh" and click the button that says, "Refresh Site."

== Screenshots ==
1. Under Tools, you'll find all settings for Force Refresh.
2. You can choose from popular refresh intervals or specify a custom one. After clicking, "Refresh site", you'll receive confirmation that you've requested connected browsers to refresh.
3. To refresh a single page or post, locate the "Force Refresh" section under any page.
4. Want to see the latest features? Clicking "View Release Notes" will display the most recent features and fixes for Force Refresh.
5. If you're having trouble, clicking on "Troubleshooting" will allow you to view the current settings for Force Refresh and allow you to enter Debugging Mode — an enhanced browser console logging mode that can be used to diagnose issues.

== Changelog ==
#### 2.17.0
_Released on April 12, 2026_

##### **New Features**
* Release notes are now grouped by minor version for easier browsing. You can also click any release to view the full details on the official GitHub repository.

##### **Changes**
* Resolves an issue where Force Refresh unnecessarily contained WordPress.org plugin marketing assets.
* Updated plugin status messaging in the admin interface to better highlight available updates, pre-release builds, and debugging mode.
* Performance enhancements and bug fixes.

#### 2.16.2
_Released on April 8, 2026_

##### **Changes**
* Performance enhancements and bug fixes.

#### 2.16.1
_Released on March 10, 2026_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.16.0
_Released on February 24, 2026_

##### **Changes**
* Update minimum PHP version to 8.2.

#### 2.15.0
_Released on February 24, 2026_

##### **Changes**
* Update minimum WordPress version to 6.3.

#### 2.14.0
_Released on November 29, 2025_

##### **New Features**
* Add support for WordPress 6.9.

#### 2.13.2
_Released on August 29, 2025_

##### **Fixes**
* Resolves an issue where Force Refresh could fail to activate on sites running PHP 8.2.

#### 2.13.1
_Released on August 9, 2025_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.13.0
_Released on April 21, 2025_

##### **New Features**
* Add support for WordPress 6.8.

#### 2.12.1
_Released on January 12, 2025_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.12.0
_Released on October 28, 2024_

##### **New Features**
* Add support for WordPress 6.7.

#### 2.11.1
_Released on September 15, 2024_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.11.0
_Released on July 7, 2024_

##### **New Features**
* Add support for WordPress 6.6.

#### 2.10.2
_Released on May 27, 2024_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.10.1
_Released on March 24, 2024_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.10.0
_Released on March 24, 2024_

##### **New Features**
* Add support for WordPress 6.5.

##### **Fixes**
* Resolves an issue where missing build files showed an unclear activation error.

#### 2.9.4
_Released on February 10, 2024_

##### **Fixes**
* Resolves an issue where icons could fail to load in the admin UI.

#### 2.9.3
_Released on December 9, 2023_

##### **Fixes**
* Resolves an issue where the Release Notes modal did not load correctly.

#### 2.9.2
_Released on November 17, 2023_

##### **Fixes**
* Resolves an issue where the admin bar confirmation message did not include the selected refresh interval.
* Resolves an issue where the refresh button label in the WordPress admin bar was incorrect.
* Resolves an issue where search results pages could refresh continuously.
* Resolves an issue where refreshing an individual page or post did not save correctly.
* Resolves an issue where Admin Bar refresh settings were not saved correctly in the plugin options.

#### 2.9.1
_Released on November 10, 2023_

##### **Fixes**
* Resolves an issue where activating Force Refresh could cause a site to crash.

#### 2.9.0
_Released on November 10, 2023_

##### **New Features**
* Add support for WordPress 6.4.

#### 2.8.3
_Released on September 9, 2023_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.8.2
_Released on August 9, 2023_

##### **Fixes**
* Resolves an issue where release notes could display duplicate periods.
* Resolves an issue where release notes could break on sites running PHP 7.4.

#### 2.8.1
_Released on August 5, 2023_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.8.0
_Released on August 5, 2023_

##### **New Features**
* Add support for leaving plugin reviews from the admin UI.
* Add support for custom refresh intervals between thirty seconds and four hours.
* Add support for viewing plugin release notes from within the admin UI.

##### **Fixes**
* Resolves an issue where dismissed admin notifications could block interaction with the rest of the admin interface.
* Resolves an issue where logo animations in the admin interface did not run with the intended timing.

#### 2.7.0
_Released on July 26, 2023_

##### **New Features**
* Add support for WordPress 6.3.

#### 2.6.1
_Released on March 4, 2023_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.6.0
_Released on June 11, 2022_

##### **New Features**
* Add support for opening the troubleshooting page directly from the main admin screen.

##### **Fixes**
* Resolves an issue where the refresh instructions read awkwardly on sites without a configured site name.

#### 2.5.2
_Released on January 23, 2022_

##### **Fixes**
* Resolves an issue where the production release workflow shipped the beta JavaScript bundle instead of the production build.

#### 2.5.1
_Released on January 23, 2022_

##### **New Features**
* Add support for troubleshooting version checks that include development version strings.
* Update WordPress version requirements.

#### 2.5.0
_Released on January 8, 2022_

##### **New Features**
* Add support for showing an admin notice when the installed plugin version is out of date.

#### 2.4.0
_Released on December 4, 2021_

##### **New Features**
* Add support for debug logging during the refresh countdown when Debug Mode is enabled.
* Add support for a troubleshooting screen with debug information and a browser-console Debug Mode toggle.

##### **Fixes**
* Resolves an issue where the refresh flow could continue after an unsuccessful refresh request.
* Resolves an issue where refresh checks could fail for site visitors.

#### 2.3.0
_Released on March 7, 2021_

##### **Fixes**
* Resolves an issue where the admin options UI did not show the default 120-second interval as selected.
* Resolves an issue where the admin bar button label incorrectly said "Force Refresh Sites."

#### 2.2.0
_Released on November 29, 2020_

##### **New Features**
* Add support for WordPress 5.5.3.
* Add support for a Vue-powered admin UI in place of the legacy Handlebars interface.

##### **Fixes**
* Resolves an issue where per-page refresh controls did not work correctly for posts whose slugs contained encoded characters.

#### 2.1.6
_Released on September 29, 2020_

##### **Fixes**
* Resolves an issue where client refresh checks ignored the configured refresh interval.

#### 2.1.5
_Released on September 17, 2020_

##### **Fixes**
* Resolves issues running Force Refresh on sites using PHP 7.2.

#### 2.1.4
_Released on September 16, 2020_

##### **Fixes**
* Resolves an issue where pages without a stored refresh version could enter a refresh loop after activation.
* Resolves an issue where the admin panel did not display the default refresh interval as the selected option.

#### 2.1.3
_Released on September 16, 2020_

##### **Fixes**
* Resolves an issue where users without the Force Refresh capability could still request refreshes.

#### 2.1.2
_Released on September 7, 2020_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.1.1
_Released on September 7, 2020_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 2.1.0
_Released on October 19, 2018_

##### **New Features**
* Add support for requesting refreshes on custom post types.

#### 2.0.0
_Released on October 11, 2018_

##### **New Features**
* Add support for HTML templating with LightnCandy.

#### 1.1.2
_Released on February 28, 2018_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 1.1.1
_Released on February 28, 2018_

##### **Fixes**
* Performance enhancements and bug fixes.

#### 1.0.0
_Released on October 5, 2017_

##### **New Features**
* Initial release.