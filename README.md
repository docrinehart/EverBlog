# EverBlog
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
