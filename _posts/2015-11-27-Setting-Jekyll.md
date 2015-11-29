---
layout: post
category: blog
tags: 
  - Jekyll
  - Ubuntu
published: true
---

## Setting Jekyll Bloging Environment

> [우분투 업데이트 서버 변경](http://harryp.tistory.com/18)을 하기를 추천한다. 

### 1. Install RVM
```
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
\curl -sSL https://get.rvm.io | bash -s stable
rvm -v
```
### 2. Install Ruby 2.1.2
```
rvm install 2.1.2
ruby -v
gem -v
```

### 3. Install bundle
```
gem install bundle
bundle -v
```

### 4. Create Gemfile refer to [Github page dependencies](https://pages.github.com/versions/)
```
source 'https://rubygems.org'

gem 'jekyll', '2.4.0'
gem 'jekyll-coffeescript', '1.0.1'
gem 'jekyll-sass-converter', '1.3.0'
gem 'kramdown', '1.5.0'
gem 'maruku', '0.7.0'
gem 'rdiscount', '2.1.7'
gem 'redcarpet', '3.3.2'
gem 'RedCloth', '4.2.9'
gem 'liquid', '2.6.2'
gem 'pygments.rb', '0.6.3'
gem 'jemoji', '0.5.0'
gem 'jekyll-mentions', '0.2.1'
gem 'jekyll-redirect-from', '0.8.0'
gem 'jekyll-sitemap', '0.8.1'
gem 'jekyll-feed', '0.3.1'
gem 'github-pages', '39'
gem 'html-pipeline', '1.9.0'
gem 'sass', '3.4.16'
gem 'safe_yaml', '1.0.4'
```

### 5. Install & Check Jekyll version
```
Bundle install
jekyll -v
```
