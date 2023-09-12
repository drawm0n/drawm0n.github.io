## This website is jekyll based
Follow instructions here for installations: https://jekyllrb.com/docs/step-by-step/01-setup/

## Testing changes locally
- Make changes in _pages/drawmon.md
- Run: `bundle exec jekyll serve`
- To test it locally open `localhost:4000` in your browser
- If your changes seems fine on locally hosted website, then push your changes
- After few minutes changes should be visible in `drawm0n.github.io` as well.

## For installing gem and all related dependencies follow this:
```
sudo apt-get install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install jekyll bundler
bundle
```
The above commands are for `ubuntu`, for windows you might need to follow this guide https://jekyllrb.com/docs/installation/windows/ and then run `bundle`.
