# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
# gem "jekyll", "~> 4.0"

# If you want to use GitHub Pages, remove the `gem "jekyll"` above and uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
end

# Filter gem dependencies are not bundled; you must bundle the filter's gem dependencies. The below list details filters with dependencies.
# gem 'rouge' for SyntaxHighlightFilter
# gem 'rinku' for AutolinkFilter
# gem 'escape_utils' for EmailReplyFilter, PlainTextInputFilter, and TableOfContentsFilter
# gem 'email_reply_parser' for EmailReplyFilter
# gem 'gemoji' for EmojiFilter
# gem 'commonmarker' for MarkdownFilter
# gem 'sanitize' for SanitizationFilter
# gem 'RedCloth' for TextileFilter

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?
