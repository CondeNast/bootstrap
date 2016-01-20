<img src="http://photos.cntraveler.com/2015/01/06/54abf33b7d23454b52671fe7_cnt-logo.jpg" width="300">

## CNT Bootstrap
This is Bootstrap without the parts that are not needed on the Condé Nast Traveler website. You can use the Bootstrap source in this repository to remove, rename, or generally edit styles in the original LESS files and to build a finished, minified CSS file.

#### How does it work?
Bootstrap applies generally-recommended styles to many basic elements like `p`, `a`, and `img`, as well as more sophisticated classes like `container`, `img-responsive`, and `btn`. Many of these styles conflict with the existing CSS on cntraveler.com. Thus, a custom copy that we can trim and pack the way we'd like.

#### What do I need?
+ Install grunt with `npm install -g grunt-cli`
+ Install dependencies with `npm install`

#### How do I run it?
Run `grunt dist` to create css that can be found in /dist. Or, read up on [more commands and the bootstrap manual itself](http://getbootstrap.com). 

`// Condé Nast Traveler Team`
