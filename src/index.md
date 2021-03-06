<center style="vertical-align:middle">
<img src="img/cljs.svg" width="120" height="150"/>
&nbsp;&nbsp;
<img src="img/react.svg" width="120" height="150"/>
</center>

# ClojureScript + React Native

Resources for developers using ClojureScript to build React Native apps.

## Discussion

* Slack: `#cljsrn` channel in [Clojurians](http://clojurians.net) Slack.
* IRC: `#clojurescript` channel on [freenode.net](https://freenode.net)

## Using

### Re-Natal

[Re-Natal](https://github.com/drapanjanas/re-natal) is the most popular and most actively developed. The consensus on #cljsrn slack channel is that it's probably the way to go. It supports React Native 0.27, Reagent and Om Next, iOS and Android, fast CLJS compilation+injection during development, and has a nice way to require native packages and static images.

### Boot-React-Native

[boot-react-native](https://github.com/mjmeintjes/boot-react-native) uses similar JavaScript techniques for hooking into the React Native packager and providing a REPL, except packaged for [boot](http://boot-clj.com/).  It's on an older version of react-native (0.20 vs 0.27) and less actively developed, but does have some cool features such as combining the React Native packager's console output with ClojureScript compiler's.  It's also a bit more lightweight than Re-Natal.

### Natal

[Natal](https://github.com/dmotz/natal) supports iOS and is based on a different approach (Ambly) that directly interacts with the device using the native ClojureScript compilation model (without the React Native packager once running): It discovers an instrumented app using Bonjour and sends the output of the compiler directly to the device using WebDAV.

## Posts

Blog posts pertaining to ClojureScript with React Native and associated tooling.
- [Writing ClojureScript Native Apps Is Easy](https://juxt.pro/blog/posts/native.html) <span style='font-size:80%'>(2017-04-20 — juxt.pro)</span>
- [From a Clean Install of Ubuntu to Re-natal](https://gadfly361.github.io/gadfly-blog/2016-11-13-clean-install-of-ubuntu-to-re-natal.html) <span style='font-size:80%'>(2016-11-13 — gadfly361.github.io/gadfly-blog)</span>
- [My experience with Clojurescript and React Native](https://medium.com/@tiensonqin/my-experience-with-clojurescript-and-react-native-81bb1d3bb2c4#.4pd73s8z2) <span style='font-size:80%'>(2016-08-06 — medium.com)</span>
- [React Native: Summing up](https://medium.com/@alwxdev/react-native-summing-up-86838441d289#.jwb21cuwn) <span style='font-size:80%'>(2016-06-24 — medium.com)</span>
- [Create iOS apps on Linux using React Native and ClojureScript](https://johannesgu.wordpress.com/2016/03/28/create-ios-apps-on-linux-using-react-native-and-clojurescript/) <span style='font-size:80%'>(2016-03-28 — johannesgu.wordpress.com)</span>
- [Yes, we can. Cross-platform native mobile applications development](https://medium.com/@alwxdev/yes-we-can-cross-platform-native-mobile-applications-development-e315300d011e#.pd3zwhfam) <span style='font-size:80%'>(2016-01-28 — medium.com)</span>
- [ClojureScript React Native Desktop](http://blog.fikesfarm.com/posts/2015-11-19-clojurescript-react-native-desktop.html) <span style='font-size:80%'>(2015-11-19 — blog.fikesfarm.com)</span>
- [Going native with om.next](https://dvcrn.github.io/clojurescript/react/2015/10/27/going-native-with-om-next.html) <span style='font-size:80%'>(2015-10-27 — dvcrn.github.io)</span>
- [Ambly Require Reload](http://blog.fikesfarm.com/posts/2015-10-07-ambly-require-reload.html) <span style='font-size:80%'>(2015-10-07 — blog.fikesfarm.com)</span>
- [GSoC Recap](http://mneise.github.io/posts/2015-09-05-gsoc-recap.html) <span style='font-size:80%'>(2015-09-05 — mneise.github.io)</span>
- [GSoC: Week 9/10 - Support for JavaScript transforms](http://mneise.github.io/posts/2015-08-04-week-9-and-10.html) <span style='font-size:80%'>(2015-08-04 — mneise.github.io)</span>
- [Using React Native Components in ClojureScript](http://blog.fikesfarm.com/posts/2015-07-24-using-react-native-components-in-clojurescript.html) <span style='font-size:80%'>(2015-07-24 — blog.fikesfarm.com)</span>
- [Reagent React Native](http://blog.fikesfarm.com/posts/2015-07-20-reagent-react-native.html) <span style='font-size:80%'>(2015-07-20 — blog.fikesfarm.com)</span>
- [Develop Now with ClojureScript for React Native](http://blog.fikesfarm.com/posts/2015-07-19-develop-now-with-clojurescript-for-react-native.html) <span style='font-size:80%'>(2015-07-19 — blog.fikesfarm.com)</span>
- [ClojureScript with React Native](http://blog.fikesfarm.com/posts/2015-07-06-clojurescript-with-react-native.html) <span style='font-size:80%'>(2015-07-06 — blog.fikesfarm.com)</span>
- [CommonJS Libs in Ambly](http://blog.fikesfarm.com/posts/2015-06-17-commonjs-libs-in-ambly.html) <span style='font-size:80%'>(2015-06-17 — blog.fikesfarm.com)</span>
- [GSoC: Week 3 - Adding CommonJS support](http://mneise.github.io/posts/2015-06-15-week-3.html) <span style='font-size:80%'>(2015-06-15 — mneise.github.io)</span>
- [GSoC: Week 2 - ClojureScript's JS dependency index](http://mneise.github.io/posts/2015-06-08-week-2.html) <span style='font-size:80%'>(2015-06-08 — mneise.github.io)</span>
- [GSoC: Week 1 - Converting JavaScript modules to Google Closure modules](http://mneise.github.io/posts/2015-06-02-week-1.html) <span style='font-size:80%'>(2015-06-02 — mneise.github.io)</span>
- [Ambly Remote Compilation and Auto-Configuration](http://blog.fikesfarm.com/posts/2015-02-16-ambly-remote-compilation-and-auto-configuration.html) <span style='font-size:80%'>(2015-02-16 — blog.fikesfarm.com)</span>

## Talks & Videos

Slides, demos, talks, _etc._ pertaining to ClojureScript with React Native and associated tooling.

- [React Native and ClojureScript - will it blend?](https://www.youtube.com/watch?v=wHgfjUQFRJU) <span style='font-size:80%'>(2017-05-08 — Oskars Liukis)</span>
- [ClojureScript in Your Pocket](https://www.youtube.com/watch?v=tHQAMrShHu8) <span style='font-size:80%'>(2017-03-31 — Dom Kiva-Meyer, Lily M. Goh)</span>
- [On iOS with React Native and Clojurescript](https://vimeo.com/191066643) <span style='font-size:80%'>(2016-11-10 — Jelle Akkerman)</span>
- [Native mobile apps with ClojureScript](https://www.youtube.com/watch?v=6IYm34nDL64) <span style='font-size:80%'>(2016-09-16 — Viktor Eriksson)</span>
- [Experience report: Clojure on iOS with React Native](https://www.youtube.com/watch?v=UHRITqJGadU) <span style='font-size:80%'>(2016-06-02 — Jelle Akkerman)</span>
- [My Adventures with React Native and ClojureScript](https://e-string.com/articles/adventures-react-native-clojurescript/) <span style='font-size:80%'>(2016-05-05 — Julio Barros)</span>
- [React Native with ClojureScript](https://github.com/langford/ReactNativeWithClojureScriptPreso/blob/master/ReactNativeWithClojureScript.pdf) <span style='font-size:80%'>(2016-02-11 — Michael Langford)</span>
- [Mobile Apps with ClojureScript](https://youtu.be/GDA-g6Ca_dQ) <span style='font-size:80%'>(2015-11-16 — Jearvon Dharrie)</span>
- [Demand Driven iOS apps with Om and React Native](https://youtu.be/oJ8t8Hc9XaE) ([Slides](http://www.slideshare.net/dvcrn/demand-driven-applications-with-omnext-and-react-native-55185632)) <span style='font-size:80%'>(2015-11-13 — David Mohl)</span>
- [Native Mobile Apps with Clojure(Script)](https://groups.google.com/forum/#!topic/boston-clojure/z2sA9rvFV7s) <span style='font-size:80%'>(2015-09-10 — Chris Vermillion)</span>
- [TXJS 2015 (iOS, Ambly portion)](https://youtu.be/nKyHvVIotBo?t=1198) <span style='font-size:80%'>(2015-07-28 — David Nolen)</span>
- [ClojureScript in Action (Ambly at 35 min)](http://www.infoq.com/presentations/clojurescript-web-ios) <span style='font-size:80%'>(2015-08-22 — David Nolen)</span>
- [Om Next (GSoC modules and Ambly portions)](https://youtu.be/ByNs9TG30E8?list=PLZdCLR02grLoBx0Y5ZrpdmLxc160PIwzQ&t=1993) <span style='font-size:80%'>(2015-07-20 — David Nolen)</span>
- [Reagent with React Native](https://youtu.be/4txql-1VXJk) <span style='font-size:80%'>(2015-07-20 — Mike Fikes)</span>
- [Coding ClojureScript React Native](https://youtu.be/Ci4uviG8S0o) <span style='font-size:80%'>(2015-07-19 — Mike Fikes)</span>
- [Using CommonJS from ClojureScript / Ambly](https://youtu.be/CS0RU2oUq7s) <span style='font-size:80%'>(2015-06-16 — Mike Fikes)</span>
- [Poor Man's Figwheel for Ambly](https://youtu.be/skuk4g-sT5k) <span style='font-size:80%'>(2015-05-30 — Mike Fikes)</span>
- [Quantum Tic Tac Toe React Native Port](https://youtu.be/7HtOTzllwTY) <span style='font-size:80%'>(2015-05-14 — Mike Fikes)</span>
- [Driving React Native with ClojureScript / Om](https://www.youtube.com/watch?v=Dt2zNemLCCk) <span style='font-size:80%'>(2015-04-25 — Mike Fikes)</span>
- [Clojure and ClojureScript Update (React Native and Ambly portions)](https://youtu.be/NvF-GZI20L4?list=PLZdCLR02grLrKAOj8FJ1GGmNM5l7Okz0a&t=1137) <span style='font-size:80%'>(2015-04-21 — David Nolen)</span>
- [Ambly iOS ClojureScript REPL](https://youtu.be/TVDkYZJW2MY) <span style='font-size:80%'>(2015-03-18 — Mike Fikes)</span>

## Misc Repos

* Matt Meintjes's [Re-Frame React Native TicTacToe](https://github.com/mjmeintjes/cljs-react-native-tictactoe).
* Nicholas Kariniemi's [proof of concept](https://github.com/nicholaskariniemi/ReactNativeCljs) for compiling ClojureScript for use on React Native for Android.
* Artem Yarulin's [react-native-eval](https://github.com/artemyarulin/react-native-eval).
* Viktor Eriksson's [re-navigate](https://github.com/vikeri/re-navigate), an example of using React Native's new Navigation with re-frame/re-natal

## Apps

Apps built using ClojureScript and React Native.

- [Fy](https://appsto.re/gb/5KjH7.i): boot-react-native + Reagent + Datascript
- [Luno Weather App](https://github.com/alwx/luno-react-native): Re-natal + reagent + React-Native-Material-Design from [Alexander Pantyuhov](https://github.com/alwx).
- [webMailReader](http://fessguid.com): Using React Native under the hood, with part of business logic in ClojureScript.
- [QTTT](https://github.com/mfikes/qttt): A port of Luke Vanderhart's web app to use Om on React Native. [Try it online](https://appetize.io/app/8kap5c0m9r3wjjdm45c416rbug?device=iphone5s&scale=75&orientation=portrait&osVersion=8.4).
- Snapability ([iOS](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1124758443&mt=8) / [Android](https://play.google.com/store/apps/details?id=net.snapability)): An OCR app built with re-natal and re-frame.
- [Lym](https://www.lymchat.com): Your interests backpack, built with clojure, cljs, re-natal, re-frame, and realm.
- [Hush](https://goo.gl/fny7Q9): Make-up store on your phone - 100% React Native app built using ClojureScript + Om Next
- [Status](https://status.im): a web3 browser, messenger, and gateway to a decentralised world of Ethereum. re-natal + re-frame + cljs + golang
- [FullContact](https://fullcontact.com): Contact management apps that help you be awesome with people. Parts of the apps built with React Native + ClojureScript + re-natal + re-frame + figwheel


## Companies

Companies using ClojureScript and React Native to build solutions.

<p><a href="http://fig.ly"><img style="width: 90px;" src="img/logos/figly.png"/></a> &nbsp;&nbsp; <a href="https://www.iamfy.co"><img style="width: 60px;" src="img/logos/fy.png"/></a> &nbsp;&nbsp; <a href="http://goo.gl/niaBLZ"><img style="width: 120px;" src="img/logos/lgs.png"/></a> &nbsp;&nbsp; <a href="https://www.lymchat.com"><img style="width: 60px;" src="img/logos/lym.png"/></a> &nbsp;&nbsp; <a href="https://status.im"><img style="width: 60px;" src="img/logos/status.png"/></a><a href="https://fullcontact.com"><img style="width: 189px;" src="img/logos/fullcontact.png"/></a></p>


<br/><center style='font-size:80%'>Maintained by Mike Fikes—<a href="https://github.com/cljsrn/cljsrn-org">submit a PR</a> if you'd like content added.</center>
