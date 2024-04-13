Concepts
 ================================================== ===================

 * JSX GUI Toolkit
 * Interface designed with reference to iOS UIKit
 * Avoid touching raw DOM and CSS
 * However, the layout is a thin wrapper of CSS
 * Optimized for smartphones
 * PC support only for Chrome/Safari

 Notes
 ================================================== ===================

 * [How to overcome application barriers with html5](http://0-9.sakura.ne.jp/pub/appsemi/start.html)
 * [Smartphone compatible, problems to be aware of](http://www.slideshare.net/HiroakiWakamatsu/ss-14011485)
 * [CSS margin is difficult](http://kojika17.com/2012/08/margin-of-css.php)
 * [Creating Fast Buttons for Mobile Web Applications](https://developers.google.com/mobile/articles/fast_buttons)
  * [FastClick](http://jsdo.it/kyo_ago/fastClick)
 * [Thinning the number of callback function executions](http://level0.kayac.com/#!2012/07/post_115.php) (JSX ver. http://jsdo.it/__gfx__/throttle)

 How to develop
 ================================================== ===================

 Clone this repository to web/example/ in the JSX repo.
 (or mv jsx-ui)

 cd $JSX/web/example
 git clone git@github.com:jsx/jsx-ui.git

 Make web && make server in the root directory of the JSX repo.

 make web
 make server

 Access the URL below.

 open http://localhost:5000/try/example/jsx-ui/example/simulator.html

 Now you can develop by editing & reloading.
