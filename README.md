## install Ruby

```
HOMEBREW_NO_AUTO_UPDATE=1 brew install rbenv  
查看可用版本
rbenv install --list 

rbenv install 3.4.1 

rbenv versions

rbenv global 3.4.1

<!-- “本地”作用域是针对各个项目的，通过项目文件夹中的 .rbenv-version 这个文件进行管理，需要将相应的 Ruby 版本号写入这个文件。所以一般设置这个选项就可以了，这个过程可以通过以下命令执行： -->
rbenv local 2.1.2

<!-- “当前终端”作用域的优先级最高。通过以下命令设置： -->

rbenv shell 3.4.1

rbenv init

source ~/.zprofile

which ruby
<!-- /Users/yongtao/.rbenv/shims/ruby -->
```

## install al-folio
gem install bundler
bundle install 
<!-- 
gem install jekyll
gem install jekyll-archives
gem install jekyll-diagrams
gem install jekyll-email-protect -->