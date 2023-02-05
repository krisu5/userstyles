# Twitter - Clean 2019 Design (Now With Light Blue™)

### 📦 [Click to install](https://github.com/krisu5/userstyles/raw/master/Twitter%20-%20Clean%202019%20Design%20(Now%20With%20Light%20Blue)/twitter_2019_clean_design_now_with_light_blue.user.css)

> Also available at [Greasy Fork](https://greasyfork.org/en/scripts/394318-twitter-clean-2019-design-now-with-light-blue) & [UserStyles.world](https://userstyles.world/style/125/twitter-clean-2019-design-now-with-light-blue)

*It's same new Twitter, except much cleaner and little bit better.* 🐦

- Toggleable option to change white background color to light blue *(enabled by default, only in "default white theme")*
- Removes annoying elements such as trends, promoted tweets, "who to follow" boxes etc.
  - And more with **recommended uBlock filterlist!**
- Other really minor tweaks / style changes.

⚠ ***Read the notes at the bottom!***

![Userstyle screenshot](https://raw.githubusercontent.com/krisu5/userstyles/master/Twitter%20-%20Clean%202019%20Design%20(Now%20With%20Light%20Blue)/screenshots/1_screenshot.jpg)

## Notes

This userstyle can't remove everything because limitations of current CSS and complexity of layout.
So I also made uBlock filterlist that removes even more elements, that are harder to do otherwise.

**[Click here to see the filterlist](https://raw.githubusercontent.com/krisu5/userstyles/master/Twitter%20-%20Clean%202019%20Design%20(Now%20With%20Light%20Blue)/filterlist.txt)**

- First, if you haven't already, install **uBlock Origin.** [Extensions for browsers listed here](https://github.com/gorhill/uBlock#ublock-origin).
  - **Uninstall Adblock Plus and other similar adblockers! Only one adblocker is necessary!** Seriously, [more info here](https://twitter.com/gorhill/status/1033706103782170625).
- Then: [How to import manually a filterlist](https://github.com/gorhill/uBlock/wiki/Filter-lists-from-around-the-web).
- Also, you can copy the filter rules and add manually to uBlock Origin if you want, but you miss the updates.

This userstyle and filterlist works **ONLY with English language** (I'm not adding support for other languages).

Works best with default white theme, but other themes are supported for element blocks.

## Extra additions for the style

Optional userstyles, made by me.

- [Twitter - Custom font](https://github.com/krisu5/userstyles/raw/master/_Misc/twitter_-_custom_font.user.css) - Change the font of Twitter to some other font on PC (my recommentation: ["IBM Plex Sans"](https://fonts.google.com/specimen/IBM+Plex+Sans))
- [Twitter - Hide FB-like DM drawer](https://github.com/krisu5/userstyles/raw/master/_Misc/twitter_-_hide_fb-like_dm_drawer.user.css) - Hide direct message box from bottom right.

## Recommended userscripts

Optional userscripts by other developers, that in my option makes Twitter so much better again.

- [I like latest tweets !](https://greasyfork.org/en/scripts/400695-i-like-latest-tweets) - Always changes to "latest tweets" in the home timeline
- [Twitter Direct](https://greasyfork.org/en/scripts/404632-twitter-direct) - Replaces t.co URLs in tweets to actual URLs
- [MoreTweetsBuster](https://greasyfork.org/en/scripts/397988-moretweetsbuster) - Redirects to actual twitter thread from "more tweets" layout when clicking Twitter link outside of Twitter (works 90% of the time)
- [Remove "more tweets" from shared links on twitter](https://greasyfork.org/en/scripts/434551-remove-more-tweets-from-shared-links-on-twitter) - Similar function to "MoreTweetsBuster" (I recommend installing both).

## Changelog

- *2023-02-05:* Some fixes since the Elon takeover. Because I fucking hate Elon and everything he has done for Twitter, I barely have interest to update this anymore. Mastodon is the future.
- *2022-03-31:* Small fixes
- *2022-03-24:* Fixes for communities
- *2022-03-09:* Minor style tweaks and removals of some rules
- *2022-02-24:* Lots of fixes and style tweaks, but most important addition is that "light blue colors" for default theme are now toggleable (enabled by default)
- *2021-10-16:* Minor fixes and cleanup
- *2021-09-09:* Fixed those blocks / tweaks that Twitter UI design update broke
- *2021-03-31:* Revue promo blocked at tweet compose modal, margin fixes for "X Retweeted / Liked" etc. text
- *2021-03-26:* More line-height fixes for links
- *2021-03-25:* Small spacing tweaks for "X Retweeted / Liked" etc. text
- *2021-03-24:* Line-height fix for links in the tweets
- *2021-03-02:* Another batch of small fixes, like "icon next to 'X Retweeted / Liked' text" fix, added "Recommended userscripts" section to README
- *2021-02-27:* Small fixes
- *2021-02-20:* Added new whitelist section, updated CSS comments for Stylus's new "sections" feature
- *2021-02-19:* Blocked "newsletters" dropdown link (promo for Revue) and redundant empty spaces on timelines, "Following" text in search suggestions to normal weight
- *2020-12-01:* Lots of misc fixes / tweaks for CSS and filterlist
- *2020-11-30:* Fixed sidebar blocks for different font sizes, fixed scrollbar CSS in the search suggestions for webkit
- *2020-10-24:* Fixed sidebar blocks & search suggestion, smaller icon & normal weight text to "X Retweeted / Liked" section
- *2020-10-16:* "Show more" link at explore page blocked, people search fixed
- *2020-09-25:* "See more" link block at search page fixed
- *2020-07-09:* "Trending now" & "Who to follow" box blocks fixed
- *2020-06-25:* Fixed / optimized regex
- *2020-06-03:* List pages added to the whitelist
- *2020-05-27:* Events page added to the whitelist
- *2020-04-22:* Fixed moments, topics and bunch of other stuff I can't remember
- *2020-04-09:* New "empty space" block
- *2020-03-22:* Sidebar boxes blocked when "Increase color contrast" is enabled, wider toaster on settings
- *2020-03-01:* Blocked empty space in the "tweet conversation" pages
- *2020-02-26:* Related to previous fix, now targets all the tweet status URLs
- *2020-02-25:* Fixed tweet status page that has "?ref_src=" URL parameter
- *2020-02-06:* Removed the footer's negative margin, code cleanup + other minor tweaks
- *2020-01-19:* Style tweaks for search suggestions (thin custom scrollbar, bit rounder box)
- *2020-01-13:* Fix people section at "hashtag search" page
- *2020-01-11:* Add missing white BG at settings section
- *2019-09-10:* "Trending now" & "Who to follow" sidebar box blocks fixed, new element blocked
- *2019-08-26:* "Link with thumbnail" element margin fixed
- *2019-08-24:* Improved toaster alert + misc. changes that I have forgot
- *2019-08-17:* "Promote Mode" & "Twitter Ads" menu links blocked
- *2019-08-16:* Moved sidebar box blocks from filterlist to userstyle + small misc. changes
- *2019-08-10:* Moved toaster alert on the bottom little bit to the left (more center to the timeline element)
- *2019-08-06:* Twitter made changes, so one of the fixes is removed from userstyle and moved to filterlist
- *2019-08-05:* Smaller icons on the notifications page, added margin to some link elements on the tweets
- *2019-08-03 r3:* More fixes to search page
- *2019-08-03 r2:* Search page fixed (now shows accounts on "people" section), explore page fixed
- *2019-08-03 r1:* Small minor fix
- *2019-08-02:* New element blocked, code cleanup
- *2019-07-29:* "Retweeted by" and "favorited by" modals fixed
- *2019-07-28 r2:* Small border-related fix
- *2019-07-28 r1:* Initial release
