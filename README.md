# ORIGNAL README
A three-row Ghost blog theme, inspired from Evernote.

## Demo:
[http://allan.li/](http://allan.li/)

## Source:
https://github.com/lialun/EverBlog

## Introduction:
### Chinese Introduction : [http://allan.li/everblog-theme/](http://allan.li/everblog-theme/)

## Advantage
1. Three rows layout,make information classification clear and accurate.
2. Small theme & Global AJAX request.
3. Dark or light theme toggle.
4. Mobile-Friendly.

## Usage:
0. download the last release version, and `Upload a theme` in Admin System-`Design`.
1. The pic in the top left corner is the `Publication logo`, upload in the Admin System-`General`, default size 70*70px.
2. Navigation list add in the Admin system-`Design`-`Navigation`.    
    You can add Tag URL which can be found in the Admin system-Tags, like "http://allan.li/tag/java/".    
    You can add Blog URL, like "http://allan.li/sql-common-resources/".    
    You can also add external URL, like "http://google.com/", it will open in new tab.
3. Open mainpage will auto load "/welcome/" blog, if don't have that blog right area will leave blank.You can change the default open blog URL in /partials/config.hbs.
4. Code highlighting plugin is Prism, support supports: css, js, bash, c, c++, c#, go, php, python, sql, groovy, http. To highlight, use markdown code-block (three ticks) and the language name: (```javascript)

# MY README
A three-row Ghost blog theme, with evernote inspired navigation

> Forked from the original [EverBlog by lialun](https://github.com/lialun/EverBlog)

##Demos:
- [Original - Chinese - allan.li](http://allan.li)
- [Forked - English - codecaptive.com](http://codecaptive.com)

##Advantages
- Three row layout, making information classification clear and accurate
- Small theme + Global AJAX request == Fast load and response times
- End-Users can toggle between dark or light theme
- Responsive / Mobile-Friendly

##Usage:
1. The pic in the top left corner is the Blog Logo, upload in the Admin System-General, default size 70*70px
2. Navigation list added in the Admin system-Navigation
    - Tag URLs, such as "http://codecaptive.com/tag/java/"
    - Blog URLs, such as "http://allan.li/sql-common-resources/"
    - External URLs, such as "http://google.com/" (which open in a new tab)
3. Change your post per page count much higher (15+), or auto load next page fails.
4. The blog which will auto load in the index page, is set in /partials/config.hbs, the default_post param, or leave blank will not auto load blog.
5. Code highlighting plugin is Prism - supports:  css, js, bash, c, c++, c#, go, php, python, sql, groovy, http. To highlight, use markdown code-block (three ticks) and the language name: (\`\`\`javascript)
>>>>>>> Touch up forked readme file
