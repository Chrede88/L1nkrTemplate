# L1nkr - Template
![L1nkr - Simple LinkTree Hugo Theme](https://raw.githubusercontent.com/chrede88/l1nkr/main/images/screenshot.png)
L1nkr is a simple LinkTree type [Hugo](https://gohugo.io) theme. The theme is designed mobile-first, with an very intuative interface.

## Installation

1) Use this template by pressing `Use this template`.
2) Clone your version of the template to your local computer:
```shell
git clone https://github.com/<username>/<reponame>
```
3) Modify `config/_default/hugo.yaml` and `config/_default/params.yaml` according to the Configuration below.
4) In a terminal/commandline, move to the newly created folder using `cd`.
5) Build a local version of your site by executing `hugo server`. You can see the site by navigating to `localhost:1313` in a browser.
6) Add a new image to the `assets/` folder, using the same name as you specified in `params.yaml`.
7) Add a new `icon.png` file to update the favicon. The png file should be 512px by 512px in size.

---

## Features

- Simple LinkTree theme, design for mobile-first.
- Automatically dark mode (based on system setttings).
- Emoji support for a fun design.
- More than 30 supported brand links.

---

## Configuration

All configuration is done in the two configuration files under `config/_default/`. The URL and site title can be set in `hugo.yaml`, all other parameters are set in `params.yaml`.

`hugo.yaml`:
```yaml
baseURL: 'https://username.github.io/L1nkr'
title: 'L1nkr'
```

`params.yaml`:
```yaml
author:
  name: "L1nkr"
  image: "author.jpeg"
  greeting: "A simple LinkTree theme for Hugo :evergreen_tree:"

links:
  - github: https://github.com/username/
  - facebook: https://facebook.com/
```

Links are defined by the name (i.e. "github" or "facebook"). The names must match one of the supported links, see list below.

### Supported Links
| **Support Links** | **Support Links** | **Support Links** | **Support Links** |
| --- | --- | --- | --- |
| github | gitlab | facebook | x-twitter |
| mastodon | linkedin | instagram | reddit |
| telegram | whatsapp | signal | codepen |
| dev | discord | orcid | slack |
| stack-overflow | stack-exchange | twitch | patreon |
| soundcloud | dribbble | tiktok | youtube |
| keybase | flickr | tumblr | kickstarter |
| snapchat | | | |
