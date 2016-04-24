source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.3'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

#=================================================================================================================================================
# rails用のslim
gem 'slim-rails'

# Devise(アカウント認証gem)
gem 'devise'

# hirb
gem 'hirb'
gem 'hirb-unicode'

# fullcalendar
gem 'fullcalendar-rails'
gem 'momentjs-rails'

# rails4からデフォルトでpjaxのようなことをやってくれるturbolinksが導入された副作用で，turbolinksが有効な状態でaタグを分でページ遷移した際，
# $(document).ready(function() {});が実行されない不具合がある．これを解消するためのgem.
gem 'jquery-turbolinks'

# パース用
gem 'nokogiri'
gem 'anemone'
gem 'addressable'

# 画像アップロード用
gem 'carrierwave'
gem 'rmagick'

# フォームから画像をアップロードする際の InvalidAuthenticityToken 対策
gem 'remotipart'

# itamae用
gem 'itamae'

# capistrano用
group :deployment do
  gem 'capistrano'
  gem 'capistrano-rails'
  gem 'capistrano-rbenv'
  gem 'capistrano-bundler'
  gem 'capistrano3-unicorn' # unicornを使っている場合のみ
end


#=================================================================================================================================================
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

