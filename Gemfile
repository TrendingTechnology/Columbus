source "https://rubygems.org"

gem 'fastlane'
gem 'cocoapods'
gem 'xcov'
gem 'danger'
gem 'danger-changelog'
gem 'danger-commit_lint'
gem 'danger-swiftlint'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
