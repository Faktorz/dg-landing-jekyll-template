#FaktorZ Website

## how to build locally
rbenv install 2.6.0
gem install bundler:1.17.3
bundle install

in _config.yml 
comment out these 2 lines 
url: "https://www.faktorz.com"
baseurl: "https://www.faktorz.com"

bundle exec jekyll serve 



## how to deply to prod
git checkout  branch-1.1
(make changes)
uncomment out these 2 lines 
url: "https://www.faktorz.com"
baseurl: "https://www.faktorz.com"

git push branch-1.1

