# DuckDuckGo - Wider, Prettier and Customizable

### 📦 [Click to install](https://github.com/krisu5/userstyles/raw/master/DuckDuckGo%20-%20Wider%20Prettier%20and%20Customizable/duckduckgo_wider_prettier_and_customizable.user.css)

> Also available at [Greasy Fork](https://greasyfork.org/en/scripts/397561-duckduckgo-wider-prettier-and-customizable)

*Customizable UserCSS for DuckDuckGo* 🦆

Toggleable features such as:
- IBM Plex Sans font (see the notes at bottom)
- Wider layout for 1920px or wider screens (**enabled by default**)
- Bigger font (**enabled by default**)
- Force hide visited link checkmark
- Delay showing sidebar in the pageload (**enabled by default**)
- Hide feedback related links

Also adds style tweaks for ["Try Google on Duck Duck Go - WF" userscript](https://greasyfork.org/en/scripts/389801-try-google-on-duck-duck-go-wf)

⚠ ***Read the notes at the bottom!***

![Userstyle screenshot, all settings enabled](screenshots/1_default.png)

**Other screenshots:**
1. [Wider layout disabled](screenshots/2_no_wider_layout.png)
2. [Bigger font disabled](screenshots/3_no_bigger_font.png)
3. [IBM Plex Sans font disabled](screenshots/4_no_ibm_plex.png)
4. [All settings enabled but with DDG's official dark theme](screenshots/5_all_settings_but_with_dark_theme.png)

## Notes

- [How to install "IBM Plex Sans" fonts](installing_ibm-plex-sans.md) (optional, unless you want the fonts)
- [How to customize settings for UserCSS style](https://github.com/openstyles/stylus/wiki/UserCSS#how-do-i-customize-usercss)
- [Recommended DDG settings](ddg_settings.md) (optional)

## Changelog

- *2021-01-28:* "IBM Plex Sans" font is not enabled by default anymore, added ["Try Google on Duck Duck Go - WF" userscript](https://greasyfork.org/en/scripts/389801-try-google-on-duck-duck-go-wf) style tweaks
- *2020-11-24:* DuckDuckGo changed their [CSP](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP), so unfortunately external webfonts won't work anymore. You need to install the fonts, if you want to keep using "IBM Plex Sans" as main font ([more info here](installing_ibm-plex-sans.md))
- *2020-09-13:* Lots of small fixes
- *2020-07-27:* Minor fixes
- *2020-06-14:* Added new setting: "hide feedback related links" (not enabled by default), fix color picker when using bigger font + misc. fixes
- *2020-05-11:* Fix sitemap under the search result when "wider layout" is enabled
- *2020-03-12:* Add breakpoint for wide layout, move webfont to the top (so it loads bit faster), prettify the code
- *2020-03-08:* Initial release