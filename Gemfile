source "https://rubygems.org"

# ここだけは自分で指定
ruby "3.4.2"
# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "7.2.2.1"

# これ以下はrailsチュートリアルに従う
gem "sassc-rails",     "2.1.2"
gem "sprockets-rails", "3.4.2"
gem "importmap-rails", "1.1.5"
gem "turbo-rails",     "1.4.0"
gem "stimulus-rails",  "1.2.1"
gem "jbuilder",        "2.11.5"
gem "puma",            "6.6.0" #RenderでPuma 5 is not compatible with Rack 3, please upgrade to Puma 6 or higher. (StandardError)となったので6にあげる
gem "bootsnap",        "1.16.0", require: false
gem "sqlite3",         "1.6.1"
gem "concurrent-ruby", "1.3.4"
gem "mutex_m",         "0.3.0"
group :development, :test do
  gem 'reline', '0.5.10'
  gem "debug",   "1.7.1", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console",         "4.2.0"
  gem "solargraph",          "0.51.1"
  gem "irb",                 "1.13.0" #ここだけrailsチュートリアルのままだとbundle installできなかったので10→13にした
  gem "repl_type_completor", "0.1.2"
end

group :test do
  gem "capybara",                 "3.38.0"
  gem "selenium-webdriver",       "4.8.3"
  gem "webdrivers",               "5.2.0"
  gem "rails-controller-testing", "1.0.5"
  gem "minitest",                 "5.18.0"
  gem "minitest-reporters",       "1.6.0"
  gem "guard",                    "2.18.0"
  gem "guard-minitest",           "2.4.6"
end