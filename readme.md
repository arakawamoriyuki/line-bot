
https://qiita.com/n0bisuke/items/ceaa09ef8898bee8369d

```
$ git clone git://github.com/nodenv/nodenv.git ~/.nodenv
$ git clone https://github.com/nodenv/node-build.git ~/.nodenv/plugins/node-build
$ echo 'export PATH="$HOME/.nodenv/bin:$PATH"' >> ~/.zshrc
$ echo 'eval "$(nodenv init -)"' >> ~/.zshrc
$ source ~/.zshrc

$ cp .envrc.sample .envrc
$ vi .envrc

$ node server.js
$ ngrok http 3000
```
