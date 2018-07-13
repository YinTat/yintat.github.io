Install: (https://jekyllrb.com/docs/windows/)
sudo apt-get update -y && sudo apt-get upgrade -y
sudo apt-add-repository ppa:brightbox/ruby-ng
sudo apt-get update
sudo apt-get install ruby2.4 ruby2.4-dev build-essential dh-autoreconf
sudo apt-get install libssl-dev
sudo gem update
sudo gem install jekyll bundler
sudo gem install commonmarker -v '0.17.9' --source 'https://rubygems.org/'
sudo gem install gemoji -v '3.0.0' --source 'https://rubygems.org/'
bundle install
sudo apt autoremove


Run:
bundle exec jekyll serve
The website is on http://localhost:4000
