# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "jekyll"
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