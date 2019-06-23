<p align="center">
    <h2 align="center">Lei Shi's domain parking page - <a href="https://www.lowercamelcase.com/">Demo</a></h2>
</p>

<p align="center">This is a simple parking page for those who bought some domains and don't know what to do with it.</p>

***

<p align="center">
    <b><a href="README.md#what-has-inside">What has inside</a></b>
    |
    <b><a href="README.md#setup">Setup</a></b>
    |
    <b><a href="README.md#settings">Settings</a></b>
</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/LeiShi1313/ParkingPage/master/screenshot.png" />
</p>


## What has inside

- [Jekyll](https://jekyllrb.com/), [Sass](http://sass-lang.com/) ~[RSCSS](http://rscss.io/)~ and [SVG](https://www.w3.org/Graphics/SVG/)
- Google Speed: [98/100](https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fsergiokopplin.github.io%2Findigo%2F);
- No JS. :sunglasses:

## Setup

0. :star: to the project. :metal:
2. Fork the project [ParkingPage](https://github.com/LeiShi1313/ParkingPage/fork)
3. Write your own `_config-YOUR_DOMAIN_NAME.yml` with your domain's url and display name. (check <a href="_config-lowercamelcase.com.yml">_config-lowercamelcase.com</a> for example)
4. Build using [Jekyll](https://jekyllrb.com/): `bundle exec jekyll build --config _config.yml,_config.yml-YOUR_DOMAIN_NAME.yml`

Or you can
<!-- Markdown snippet -->
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/LeiShi1313/ParkingPage)

## Settings

You must create your own `_config-YOUR_DOMAIN_NAME.yml` to customize your site.

```
# main text of home
url: https://www.lowercamelcase.com
# For display purpose
domain_name: "lowerCamelCase.com"
...

You can also change external_links, profile img in `_config.yml`.
```

[MIT](http://kopplin.mit-license.org/) License © Lei Shi
