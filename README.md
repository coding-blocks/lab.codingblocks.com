# Coding Blocks Lab <http://lab.codingblocks.com>

CB Lab is an open source projects playground. This repository is a Jekyll
site that forms the website - <http://lab.codingblocks.com>

This uses the [Harmony Theme](THEME.md) on top of Jekyll.

## Adding New Projects

Make sure you have `ruby` and `ruby-gems` installed.
Then make sure you have `rake` installed.

```shell
gem install rake
```

We have a rake task `new_project`, which you can run like this -

```shell
rake 'new_project["WebIDE", "An IDE in a Webapp to compile and test code online"]'
```