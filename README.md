# octopress-github-readme-stats
Octopress (Jekyll) plugin to show [github-readme-stats](https://github.com/anuraghazra/github-readme-stats).

## Installation

* HTML:
    * Copy **source/_includes/custom/asides/github-readme-stats.html** to your **source/_includes/custom/asides/**.
    * Or you can put codes in **github-readme-stats.html** anywhere you like.

## Usage

Add following configurations in your **_config.yml**:

```
# Show stats or not
github_readme_stats_stats: true
# Set theme
github_readme_stats_theme: graywhite
# Show icons or not
github_readme_stats_icons: true
# Count private repository or not
github_readme_stats_private: false

# Show languages or not
github_readme_stats_lang: true
# Set number of languages to show (default: 8)
github_readme_stats_lang_count: 20
# Set repositories to be excluded
github_readme_stats_exclude_repo: rcmdnk.github.io
```
