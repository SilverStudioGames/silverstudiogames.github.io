---
title: Download
---
{% assign version = site.game_version | split: "." %}
{% assign major_version = version | slice: 0, 2 | join: "." %}
{% assign patches = version[2] | minus: 1 | default: 0 %}
{% capture old_version %}{{ version[0] }}.{{ version[1] | minus: 1 }}.x{% endcapture %}

Before you download anything, please take note of the following:
- This mod is entirely free.
- The original Witch Trainer game is not needed. Just download, extract, and play.
- Saves from version **{{ old_version }}** and earlier are **not compatible**.
- MEGA links will always stay up to date with the latest version.
- This game features adult content. You must be 18 years of age or older to play.

# Game version {{ site.game_version }}

<a href="https://mega.nz/#F!d4ABCKjb!8dtunG_y3kLNsyuBpEZfDA" class="btn">Windows, Mac & Linux</a>
<a href="https://mega.nz/#F!VgIhXaZS!42Db1y1xNO-fLOUSCb8e7w" class="btn">Android (ARM & x86/x64)</a>

{% if patches > 0 %}

# Patch {{ site.game_version | truncate: 4, "" }}.# to {{ site.game_version }}

- Supported versions: **{{ major_version }}**{% for i in (1..patches) %}, **{{ major_version }}.{{ i }}**{% endfor %}
- Unpack patch contents in the game directory and overwrite existing files.

<a href="https://mega.nz/file/R9QlkADB#ovcm5Tve5L54YExNLcaeWIoQpqcd2U4yBIwUiRrjZgg" class="btn">Windows, Mac & Linux</a>

{% endif %}

# More information

[Changelog & Patch notes](https://docs.google.com/document/u/2/d/e/2PACX-1vReRMkJg-CgAkLS19jUcSmMG2xwuWCLc9qlU9Z2_OAFADYJxiGXkwh7UCOoBifxvS7hsXK6Q4Larl2-/pub)

[FAQ & Troubleshooting](https://github.com/SilverStudioGames/WT-Silver/wiki/Help)

[Source code on GitHub](https://github.com/SilverStudioGames/WT-Silver)
