=== Auto Load Next Post ===
Contributors:      sebd86
Donate link:       https://autoloadnextpost.com/donate.htm
Tags:              auto load posts, scroll, scroll posts, post scroller, scrolling, infinite scroll, infinite scrolling, AJAX, endless, history, post history, browsing history, views, postviews, google analytics
Requires at least: 4.3
Tested up to:      4.6
Stable tag:        trunk
License:           GPLv2 or later
License URI:       http://www.gnu.org/licenses/gpl-2.0.html

Gain more post views as your site viewers continue reading your loading blog posts as they scroll down the page.

== Description ==

[youtube https://www.youtube.com/watch?v=EvBCPXVe2U4]

= What is Auto Load Next Post? =
Auto Load Next Post simply loads the next post on your blog automatically once the user has reached the bottom of the initial post and is repeated until there are no more posts to load.

In order to do this, the WordPress theme in use needs to have a post navigation at the end of each single blog post which the plugin will then detect to collect the previous post URL to load the next post. The JavaScript then loads that post by inserting the content via a partial template underneath the parent post.

As it does this, the address bar and page title will change to that post it has loaded. Should you refresh the browser, the post you were currently reading would load as the new initial post.

Your browser also retains the history of the posts that were viewed on the blog allowing you to go back to a previous post.

= First Time Users =
If you are a developer then following [the documentation](https://github.com/seb86/Auto-Load-Next-Post/wiki) should be easy to understand how to setup the plugin. By default when the plugin is activated, the settings are ready to be used with WordPress's core theme Twenty Fifteen which is also standard for most WordPress themes hosted here.

If you are not a developer then I do provide [direct support](https://sebastiendumont.com/product/direct-support-auto-load-next-post/) where I can do this for you as a service.

= Features =
* Use action hooks to load content before and after the next post has loaded. [Example Plugin](https://github.com/seb86/Auto-Load-Next-Post-Hooks-Example)
* Hide Comments. ( Optional )
* Track each post load with Google Analytics. ***Requires Google Analytics to be installed for this to work.***
* Over-writable template file.
* WordPress Network / Multisite support.
* Works with any theme that follows the [Theme development standards](https://codex.wordpress.org/Theme_Development#Theme_Development_Standards).

> #### Auto Load Next Post Premium
> There's an even better version of the plugin coming out soon with the following extra features:<br />
>
> - Custom Post Type Support<br />
> - Media Attachments Support<br />
> - Overwritable Template for Pages<br />
> - Supports more popular themes with auto setup detection<br />
> - [JetPack](https://wordpress.org/plugins/jetpack/) Supported<br />
> - [Related Posts for WordPress](https://wordpress.org/plugins/related-posts-for-wp/) Supported<br />
> - Priority Email Support<br />
>
> [More information](https://autoloadnextpost.com/?utm_source=wp-plugin-repo&utm_medium=link&utm_campaign=after-features-info-link) | [Sign up to be notified >>](http://eepurl.com/bvLz2H)

= Contributing =
If you are a developer and love the plugin and would like to [contribute](https://github.com/seb86/Auto-Load-Next-Post/blob/master/CONTRIBUTING.md) to it then I look forward to your ideas and suggestions. Any contributor that has helped support and made the plugin better will be credited.

= Support and Issue Reporting =
You can use the WordPress.org forum for [community support](https://wordpress.org/support/plugin/auto-load-next-post) and I will do my best to respond in a timely fashion. You may also find that a topic similar to yours has already been posted so please check them out first as you may find an answer has already been given.

If none of the tickets, opened or resolved does not have the answer then you can create a new support ticket. Please be descriptive as possible and provide the name and location of the theme you are wanting to use.

I also provide [direct support](https://sebastiendumont.com/product/direct-support-auto-load-next-post/) which makes you priority.

If you spot a bug within the plugin, you can of course log it as an [issue](https://github.com/seb86/Auto-Load-Next-Post/issues) on GitHub where I can act upon it more efficiently.

= Demo =
Want to see how it works? [Go to the demo site](http://demo.autoloadnextpost.com) and view a post. Scroll down to the end of the post and see the next post load.

= Support by Donating =
[Donations](https://autoloadnextpost.com/donate.htm) of any sum help keep this plugin actively developed and supported. Your support goes along way in making this plugin better. [Make a Donation](https://autoloadnextpost.com/donate.htm)

= Leave a Review =
Reviews are very helpful so please consider spending a minute or two leaving a [review](https://wordpress.org/support/view/plugin-reviews/auto-load-next-post?rate=5#postform) and tell me what you think about the plugin. It would be most appreciated.

= Languages and Translation Support =
Languages are now downloaded when needed from WordPress.org so they will no longer be part of the plugin in the future. If you would like to help translate the plugin, please read the [translate handbook](https://make.wordpress.org/polyglots/handbook/) to get started. [Start Translating](https://translate.wordpress.org/projects/wp-plugins/auto-load-next-post) for Auto Load Next Post.

**Libraries Used**

- [chosen](https://github.com/harvesthq/chosen)
- [jQuery.history](https://github.com/browserstate/history.js)
- [jQuery.tiptip](https://github.com/drewwilson/TipTip)
- [scrollspy](https://github.com/thesmart/jquery-scrollspy)

The libraries above are used with the plugin.

> #### PHP Requirement
> This plugin requires PHP version 5.3 or higher.<br />
> If you're still at PHP 5.2, it's time to update. [Read here why and how](http://www.wpupdatephp.com/update/)<br />
> Updating to a newer PHP version is almost always done in minutes and free of charge!

**More information**

- [Visit Auto Load Next Post website](https://autoloadnextpost.com)
- [Auto Load Next Post plugin on GitHub](https://github.com/seb86/auto-load-next-post)
- Other [WordPress plugins](http://profiles.wordpress.org/sebd86/) by [Sébastien Dumont](https://sebastiendumont.com)
- Contact Sébastien on Twitter: [@sebd86](http://twitter.com/sebd86)

== Installation ==
Installing "Auto Load Next Post" can be done either by searching for "Auto Load Next Post" via the "Plugins > Add New" screen in your WordPress dashboard, or by using the following steps:

1. Download the plugin via WordPress.org
2. Upload the ZIP file through the 'Plugins > Add New > Upload' screen in your WordPress dashboard.
3. Activate the plugin through the 'Plugins' menu in WordPress.
4. Go to the plugin settings page 'Settings > Auto Load Next Post'.
5. Enter each of the containers specified for the theme you are using and press "Save Changes".

Once you have activated the plugin, you may get an admin notice telling you that you have not declared support for the plugin. This is perfectly normal and with a little setting up, the notification will remove automatically. There are two buttons. The first leads you to documentation to help you support the plugin in your theme. The second allows you to force hide the admin notice. - This notification does not show for any of WordPress core themes as they are already supported.

See [the documentation](https://github.com/seb86/Auto-Load-Next-Post/wiki) for more information and screenshots.

== Frequently Asked Questions ==

> #### Auto Load Next Post Premium
> There's an even better version of the plugin coming out soon with the following extra features:<br />
>
> - Custom Post Type Support<br />
> - Media Attachments Support<br />
> - Overwritable Template for Pages<br />
> - Supports more popular themes with auto setup detection<br />
> - [JetPack](https://wordpress.org/plugins/jetpack/) Supported<br />
> - [Related Posts for WordPress](https://wordpress.org/plugins/related-posts-for-wp/) Supported<br />
> - Priority Email Support<br />
>
> [More information](https://autoloadnextpost.com/?utm_source=wp-plugin-repo&utm_medium=link&utm_campaign=faq-info-link) | [Sign up to be notified >>](http://eepurl.com/bvLz2H)

= How do I enable theme support for the plugin? =

Simple add this to your ***functions.php*** file.<br />
> ```add_theme_support('auto-load-next-post');```<br />

Then setup the selectors for your theme in the settings page.

= Where's the settings screen? =

Settings > Auto Load Next Post.

= Is overriding the template file required? =

No. This was put in place to support themes that have coded their template files differently from [WordPress theme standards](https://codex.wordpress.org/Theme_Development#Theme_Development_Standards).

= How can I override the default template file? =

Simply create a new folder in your theme like so: ***your-theme/auto-load-next-post/*** and copy the template file ***content-partial.php*** into that new folder. Modify it to match how your theme's content is loaded. Once complete it will load that template file instead.

= Is it compatible with the JetPack's related posts module? =

Yes, you will need to follow [this documentation](https://jetpack.com/support/related-posts/customize-related-posts/#shortcode) provided by JetPack in order to apply it to the template file ***content-partial.php*** within your theme using the shortcode. You can also use the action hooks already put in place within the template file instead if you don't need to copy the template file to your theme.

= You mentioned action hooks to load content before and after the next post has loaded. What are they? =

The [action hooks](https://github.com/seb86/Auto-Load-Next-Post/wiki/Hooks) are documented on the GitHub repository along with an example on how to use them. I have also prepared a [plugin](https://github.com/seb86/Auto-Load-Next-Post-Hooks-Example) that shows you an example of added content using the hooks.

= After the first post has loaded, all I get is the same post over and over again. Why is that? =

Some themes may or may not need the template ***content-partial.php*** file created in your theme. If you have not done so then you will have to create your own to support the theme structure. If you have already done that then you may have placed the post navigation outside of the post query. You need to place it inside the loop. If that is not the case then you have not included the content of the post correctly according to the theme.

= Does the plugin detect my theme and insert the correct selectors for me? =

No it does not, but this is something I am working on for the premium version. However this will only work with themes that have been tested and approved. It will not have the ability to scan code and identify the elements for you. This is mainly because not all themes use the same selectors.

= My theme does not work with the plugin, what do I do? =

First check that you have a post navigation at the end of your post. If one does exists then you may need to copy and modify the template file ***content-partial.php*** in order to support your theme. Not all themes are coded the same way so some alterations will be needed. If you need help with this then I provide [direct support](https://sebastiendumont.com/product/direct-support-auto-load-next-post/) on request.

= I'm confused about the post order. Why is the plugin called Auto Load Next Post? =

Well, WordPress loads posts in descending order by default so the next post is the previous post and a user reads content going down not up so it loads the next post, not previous.

= How can I get the Google Analytics option to work? =

You first need to have Google Analytics installed on your site. Either by inserting the analytics into your theme yourself or by using the [Google Analytics by MonsterInsights](https://wordpress.org/plugins/google-analytics-for-wordpress/) plugin.

= Does Auto Load Next Post support WordPress Network / Multisite websites? =

It does. Just make sure that you activate the plugin on the site you want it used on and then make sure the selectors match the theme the site is using.

== Screenshots ==
1. PHP Warning Admin Notification
2. Theme Support Admin Notification
3. Admin Settings Page

== Changelog ==
= 29th August 2016 =
* No version change just assets and readme.txt file updated.

= 1.4.7 : 4th April 2016 =
* Added the Russian (Russia) translation.
* Updated the English (United Kingdom) translation.
* Updated the Italian (Italy) translation.

= 1.4.6 : 3rd April 2016 =
* Corrected links within the readme.txt file.
* Provided a list of extra features coming with Auto Load Next Post Premium.
* Improved copy.
* Added two additional help tabs on the plugin settings page.
* Updated the F.A.Q's.
* Updated the uninstall.php file.
* Updated the POT file.
* Fixed undefined issue with Google Analytics.
* Removed all console.log and console.error in the Javascript.
* Tested up to WordPress 4.4.2

= 1.4.5 : 30th November 2015 =
* Added the English (United Kingdom) translation.
* Updated the Italian (Italy) translation.

= 1.4.4 : 29th November 2015 =
* Fixed the activation of the plugin from the broken update in version 1.4.3
* Removed code that is not needed and certain parts that are not for the free version of Auto Load Next Post.
* Removed additional whitespace in the code making the plugin just a little bit lighter.
* Improved the WP Update Php class originally created by Coen Jacobs. Also renamed the class a little so that it doesn't cause any conflicts with other plugins when activating.
* Updated the copy in the settings page.
* Updated the French translation.

= 1.4.3.1 : 20th October 2015 =
* Re-deployed v1.4.3 update as it failed using Ship by Big Bite Creative. Sorry about that. :(

= 1.4.3 : 19th October 2015 =
* Corrected undefined function for Google Analytics tracking in the JavaScript.
* Improved Google Analytics. Now detects old, classic, current and Yoast method of tracking pageviews.
* Changed the default content container setting to match Twenty Fifteen.
* Core themes are supported except for Twenty Eleven. Theme notification only shows now if not a core theme.
* Corrected a loading issue of the template file should the theme have one also.
* Improved the partial content template file. Now has a fallback. Should be more compatible with themes.
* Added a support tab to the plugin settings page.
* Added a upgrade link on the plugins page.
* Added a community support link on the plugins page.
* Added the German translation.
* Redefined the constants.
* Moved admin functions under the directory 'includes/admin'
* Moved library assets under a new folder for both CSS and JavaScript.
* Added PHP detection.
* Improved copy in the settings page and the help tab.
* Updated the default localization file.
* Removed public variables and hardcoded them into the plugin instead.
* Removed whitespace.
* Removed @return void on __construct() functions.
* Cleaned up the code.

= 1.4.2 : 31st July 2015 =
* Added two languages for localizing the plugin settings page. Français (French)(France) and Română (Romanian).

= 1.4.1 : 13th June 2015 =
* Added many action hooks in template file 'content-partial.php' - See documentation for a list of hooks.
* Removed an error from the admin side when debug is enabled.

= 1.3.2 : 20th May 2015 =
* Added more theme support with compatible theme template file which can be overridden.
* Added option to enable auto loading posts for specific post types.
* Added option for comments. Now you can choose to show or hide rather than forcing it to hide automatically.
* Added Chosen (v1.4.2) Javascript by [Harvest](http://harvesthq.github.io/chosen/)
* Added console.logs in the Javascript for debugging.
* Corrected text domain name in plugin header.
* Corrected access to function load_file() from private to public
* Corrected access to function register_scripts_and_styles() from private to public
* Corrected error with uninstall.php file
* Moved function register_scripts_and_styles() to class-auto-load-next-post-admin.php
* Filtered the Javascript to load only on singular posts and the enabled post types.
* Removed security issue in the main plugin file by accessing $GLOBALS directly.
* Removed all closing PHP tags omitting at the end of each file.

= 1.0.0 : 4th April 2015 =
* Initial version

== Upgrade Notice ==
= 1.4.7 : 4th April 2016 =
* Added the Russian (Russia) translation.
* Updated the English (United Kingdom) translation.
* Updated the Italian (Italy) translation.

