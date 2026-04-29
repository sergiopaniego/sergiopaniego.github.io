source 'https://rubygems.org'
group :jekyll_plugins do
    gem 'jekyll'
    gem 'jekyll-archives'
    gem 'jekyll-diagrams'
    gem 'jekyll-email-protect'
    gem 'jekyll-feed'
    gem 'jekyll-imagemagick'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-target-blank'
    gem 'jekyll-twitter-plugin'
    gem 'jemoji'
    gem 'mini_racer'
    gem 'unicode_utils'
    gem 'webrick'
end
group :other_plugins do
    gem 'httparty', '~> 0.21.0'
    gem 'feedjira'
end

# Pinned: nokogiri >= 1.18 requires Ruby >= 3.2, but liquid 4.0.3 (via
# jekyll 4.2.2) calls String#tainted?, which Ruby 3.2 removed. Lifting
# this pin requires upgrading jekyll/liquid as well.
gem 'nokogiri', '~> 1.16.5'

# Pinned: activesupport >= 7.2 requires Ruby >= 3.1. Pulled in transitively
# by html-pipeline (>= 2) via jemoji, so dependabot will otherwise propose
# breaking bumps. Lift together with the nokogiri pin.
gem 'activesupport', '~> 7.0.7'

# Pinned: multi_xml >= 0.8 requires Ruby >= 3.2. Pulled in transitively
# by httparty (>= 0.5.2), so it can cascade independently of the httparty
# pin above. Lift together with the nokogiri pin.
gem 'multi_xml', '~> 0.6.0'

# Pinned: public_suffix >= 7 requires Ruby >= 3.2. Pulled in transitively
# by addressable, so dependabot will otherwise propose breaking bumps.
# Lift together with the nokogiri pin.
gem 'public_suffix', '~> 4.0.7'
