# Install Requirements and Run the Site

Please check if versions are up-to-date, here:
[Jekyll on macOS](https://jekyllrb.com/docs/installation/macos/)

Install on macOS:
```bash
brew install chruby ruby-install xz
ruby-install ruby 3.1.3
```

Add the following to your .zshrc: 
```zsh
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.1.3" >> ~/.zshrc # run 'chruby' to see actual version
```

Relaunch your terminal and check the ruby version (should be 3.1.3):
```bash
ruby -v
```

Then install jekyll and bundler: 
[Instructions](https://jekyllrb.com/docs/#instructions)

```bash
gem install jekyll bundler
```

Then build the site and make it available on a local server:
```bash
bundle exec jekyll serve
```

Browse to http://localhost:4000

# Based on MMistakes' Minimal Mistakes Jekyll Theme

commit: 8a67ce8e41ec850f2d7c373aa47739b2abfee6f1