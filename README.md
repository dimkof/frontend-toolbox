# frontend-toolbox

Actively maintained list of useful web developments tools, libraries, assets and any other open-source goodies.

Shamelessly aggregated from the following resources:

- [Brunch plugin wiki](https://github.com/brunch/brunch/wiki/Plugins)
- [Tooling & The Webapp Development Stack](https://gist.github.com/2713513): Notes from a talk by Paul Irish
- [DailyJS](http://dailyjs.com/): Excellent JavaScript blog
- [JavaScript Jabber Podcase](http://javascriptjabber.com/): Kick-ass JavaScript podcast
- [Smashing Magazine](http://www.smashingmagazine.com/): Best web-development magazine
- [Hipster Dev Stack](http://hipsterdevstack.tumblr.com/): A curated directory of artisanal development tools that we used to like before they went mainstream.
- [NetTutsPlus](http://net.tutsplus.com/): Web development tutorials, from beginner to advanced
- [Sublime Text Workflow That Beats Coda and Espresso](http://tarantsov.com/blog/2012/02/sublime-text-workflow-that-beats-coda-and-espresso/)

_"★" recommended and currently used by the maintainer_

## General

- ★ [HTML5 Spec for Web Developers](http://developers.whatwg.org/): This specification is intended for authors of documents and scripts that use the features defined in this specification.
- [DocHub](http://dochub.io/): Alternative documentation repository for: CSS, HTML, JavaScript, DOM, jQuery, PHP, Python
- [Hypertext Transfer Protocol -- HTTP/1.1](http://www.w3.org/Protocols/rfc2616/rfc2616.html): you should read through it at least once
- [ReFiddle](http://refiddle.com/): Regular Expression (regex) tester... better than the rest
### Compatibility
- [When can I use...](http://caniuse.com/): Compatibility tables for support of HTML5, CSS3, SVG and more in desktop and mobile browsers.
- [HTML5 & CSS3 Readiness](http://html5readiness.com/): We don't have to wait for entire specs to be completed, we can start using some hawtness now.
- [HTML5 Please](http://html5please.com/): Use the new and shiny responsibly.
- [HTML5 Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)


#### UI Toolkits

- [Twiter Bootstrap](http://twitter.github.com/bootstrap/)
  - [Compass Twitter Bootstrap](https://github.com/vwall/compass-twitter-bootstrap)
- [jQuery UI](http://jqueryui.com/demos/)

### Documentation

- ★ [Docco](http://jashkenas.github.com/docco/): Quick and dirty, literate-programming documenation generator
- [Groc](http://nevir.github.com/groc/): is an attempt to further enhance the idea [of Docco]

### Build Tools, Assemblers, et al

- ★ [Yeoman](http://yeoman.io/): a robust and opinionated client-side stack, comprised of tools and frameworks that can help developers quickly build beautiful web applications.
- ★ [Brunch](http://brunch.io/): A lightweight approach to building HTML5 applications with an emphasis on elegance and simplicity.
- ★ [Middleman](http://middlemanapp.com/): a static site generator using all the shortcuts and tools in modern web development.
- ★ [Grunt](http://gruntjs.com/): a task-based command line build tool for JavaScript projects
- [LiveReload](http://livereload.com/): CSS edits and image changes apply live. CoffeeScript, SASS, LESS and others just work. (OSX only)
- [CodeKit](http://incident57.com/codekit/): CodeKit helps you build websites faster and better. (OSX only)
- [Lumbar](http://walmartlabs.github.com/lumbar/): Lumbar is a js-build tool that takes a general codebase and list of platforms to generate modular platform specific applications. (from Walmart Labs)

## JavaScript

- [Modernizr](http://modernizr.com/): detects HTML5 and CSS3 features in the user’s browser.
- [Underscore](http://underscorejs.org/): JavaScript utility belt
- [JSON3](http://bestiejs.github.com/json3/): JSON parser/stringifier
- [Idiomatic JS](https://github.com/rwldrn/idiomatic.js): Principles of Writing Consistent, Idiomatic JavaScript
- [JavaScript Garden](http://bonsaiden.github.com/JavaScript-Garden/): growing collection of documentation about the most quirky parts JavaScript

- [PhantomJS](http://phantomjs.org/): Headless WebKit with JavaScript API

### Modules and Script loaders

- [RequireJS](http://requirejs.org/) The awesomest AMD script loader
- [LabJS](http://labjs.com/) script loader
- [YepNope](http://yepnopejs.com/) conditional loader for polyfills

- [Bower](http://twitter.github.com/bower/) package manager for the web
- [Volo](https://github.com/volojs/volo) Create front end projects from templates, add dependencies, and automate the resulting projects
- [Ender](http://ender.no.de/) the no-library library

### Books

- [JSbooks](http://jsbooks.revolunet.com/): crazy collection of free JS books
- [JavaScript:The Definitive Guide](http://shop.oreilly.com/product/9780596805531.do)
- [JavaScript Patterns](http://shop.oreilly.com/product/9780596806767.do)
- [Maintainable JavaScript](http://shop.oreilly.com/product/0636920025245.do)
- [JavaScript Web Applications](http://www.amazon.com/JavaScript-Web-Applications-Alex-MacCaw/dp/144930351X)

#### Free/online

- [Eloquent JavaScript](http://eloquentjavascript.net/)
- [Essential JavaScript Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/)

### jQuery

- [jQuery](http://jquery.com/): Write less; do more.
- [Zepto](http://zeptojs.com/): jQuery alternative for mobile apps (super light-weight)
- [jQAPI](http://jqapi.com/): Alternative jQuery Documentation

#### Useful jQuery Plugins

- [FormatCurrency](http://code.google.com/p/jquery-formatcurrency/)
- [MaskedInput](http://digitalbush.com/projects/masked-input-plugin/)

### Mobile

- [Zepto](http://zeptojs.com/)
- [jQuery Mobile](http://jquerymobile.com/)

### Testing

- [Jasmine](http://pivotal.github.com/jasmine/)
- [Mocha](http://visionmedia.github.com/mocha/)
- [QUnit](http://docs.jquery.com/QUnit)

- [JSTestDriver](http://code.google.com/p/js-test-driver/) remote, automated testing of javascript on different browsers
  - [Jasmine JSTD](https://github.com/ibolmo/jasmine-jstd-adapter) adapter for using Jasmine

- [SinonJS](http://sinonjs.org/)
- [Chai](http://chaijs.com/): assertions lib
  - *should*: foo.should.be.a('string')
  - *expect*: expect(foo).to.be.a('string')
  - *assert*: assert.typeof(foo, 'string')

- [should.js](https://github.com/visionmedia/should.js) 'should' style assertions
- [expect.js](https://github.com/LearnBoost/expect.js) 'expect' style assertions


### [Transcompilation](http://en.wikipedia.org/wiki/Source-to-source_compiler) Languages

- ★[CoffeeScript](http://coffeescript.org/): a little language that compiles into JavaScript
  - [Little Book on CoffeeScript](http://arcturo.github.com/library/coffeescript/)
  - [CoffeeScript Tutorials](http://www.youtube.com/playlist?list=PL399DF0B74063889F&feature=plcp)
- [IcedCoffeeScript](http://maxtaco.github.com/coffee-script/): drop-in replacement interpreter for CoffeeScript with **async control flow semantics**.
- [LiveScript](http://gkz.github.com/LiveScript/): aims for increased expressiveness and code beauty, while adding features to assist in functional style programming, imperative and object oriented programming, and has an optional class system with inheritance, calls to super, and more.
- [Roy](http://roy.brianmckenna.org/): an experimental programming language that targets JavaScript and tries to meld JavaScript semantics with some features common in static functional languages.

### Linters

Tools to detect errors (syntactic, semantic, otherwise) and potential problems in JavaScript code.

- [JSHint](http://www.jshint.com/): New hotness 
  - [Sublime Linter](https://github.com/SublimeLinter/SublimeLinter): Sublime plugin for JSHint.
- [JSLint](http://www.jslint.com/): Old and busted.

### Frameworks ([MV* et al](http://lostechies.com/derickbailey/2011/12/23/backbone-js-is-not-an-mvc-framework/))

- [Backbone.js](http://documentcloud.github.com/backbone)
  - [Backbone Fundamentals](http://addyosmani.github.com/backbone-fundamentals/)
  - [Backbone Koans](https://github.com/larrymyers/backbone-koans)
  - [Marionette](http://marionettejs.com/): composite app architecture on top of backbone
  - [Chaplin](https://github.com/chaplinjs/chaplin): application architecture
  - [Backbone LocalStorage](https://github.com/jeromegn/Backbone.localStorage)
- [Ember.js](http://emberjs.com)
- [AngularJS](http://angularjs.org)
- [Spine](http://spinejs.com)
- [KnockoutJS](http://knockoutjs.com) (MVVM)
- [YUI](http://yuilibrary.com)
- [Batman.js](http://batmanjs.org)
- [Closure](http://code.google.com/closure/library/)
- [Google Web Toolkit](https://developers.google.com/web-toolkit/)
- [CanJS](http://canjs.us)
- [Meteor](http://meteor.com)
- [Derby](http://derbyjs.com)
- [SocketStream](http://www.socketstream.org) + [jQuery](http://jquery.com)
- [Ext.js](http://www.sencha.com/products/extjs)
- [JavaScriptMVC](http://javascriptmvc.com)

- [RivetsJS](https://github.com/mikeric/rivets) declarative data-binding; framework agnostic

- _there's lots more but, comon.... they're not as good :)_

## CSS

- [CSS3.info](http://www.css3.info/): All you ever needed to know about CSS3
- [CSS3 Please](http://css3please.com/): The Cross-Browser CSS3 Rule Generator
- [Semantic Grid System](http://semantic.gs/): Page layout for tomorrow (SCSS, LESS, Stylus)

### Linters
  - [Recess](http://twitter.github.com/recess/) Twitter's CSS hinter

### Preprocessors

- [Stylus](http://learnboost.github.com/stylus/): Expressive, dynamic, robust CSS
  - [Nib](https://github.com/visionmedia/nib)
- [Sass](http://sass-lang.com/): Sass is an extension of CSS3, adding nested rules, variables, mixins, selector inheritance, and more.
  - [SASS Tutorials](http://www.youtube.com/playlist?list=PL2CB1F80266E986EA&feature=plcp)
  - [Compass](http://compass-style.org/): Compass is an open-source CSS Authoring Framework.
    - [Compass Tutorials](http://www.youtube.com/playlist?list=PL45DD77A4CCA76ED3&feature=plcp)
    - [Compass Twitter Bootstrap](https://github.com/vwall/compass-twitter-bootstrap)
  - [Susy](http://susy.oddbird.net/):Responsive grids for Compass.
  compas

## Editors

### Sublime Text 2

Install and use [Sublime Text 2 Package Control](http://wbond.net/sublime_packages/package_control) for these and other plugins.

- ★ [ZenCoding](https://github.com/sublimator/ZenCoding): editor plugin for high-speed HTML coding and editing
- ★ [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview): A simple plugin to help you preview your **markdown** files; works with _LiveReload_.
- ★ [LiveReload](https://github.com/dz0ny/LiveReload-sublimetext2): A web browser page reloading plugin.
- ★ [Sidebar Enhancements](https://github.com/titoBouzout/SideBarEnhancements): Enhancements to Sublime Text sidebar. Files and folders.
- ★ [SublimeREPL](https://github.com/wuub/SublimeREPL):run an interpreter inside ST2
- ★ [Git](https://github.com/kemayo/sublime-text-2-git): Plugin for some git integration
- ★ [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter): Inline lint highlighting
- ★ [JsFormat](https://github.com/jdc0589/JsFormat): javascipt formatting plugin (prettifier)
- [Sublime Prefixr](http://wbond.net/sublime_packages/prefixr): run CSS through the [Prefixr](http://prefixr.com/) API
- [Search StackOverflow](https://github.com/ericmartel/Sublime-Text-2-Stackoverflow-Plugin): Simple search on Stack Overflow utility

#### Themes (TextMate or SublimeText)

- [NodeJS](http://textmatetheme.com/node-js): dark
- [Tomorrow](https://github.com/chriskempson/tomorrow-theme): multiple, dark/light
- [Django](https://code.djangoproject.com/attachment/wiki/TextMate/Django.tmTheme.zip): dark green

## Design

### Icons

- ★ [FontAwesome](http://fortawesome.github.com/Font-Awesome/): The iconic font designed for use with Twitter Bootstrap
- [IconSweets](http://iconsweets2.com/): a huge FREE icon set containing over a 1,000+ icon
- [Glyphicons](http://glyphicons.com/): designed primarily for toolbars and navigation bars in OS X Lion, the application for iPhone, iPhone 4, iPad and other Apple devices. (CC license)
- [Glyphish](http://www.glyphish.com/): Free set published under a Creative Commons Attribution license
- [FamFamFam](http://www.famfamfam.com/lab/icons/): oldie, but goodie
- [LED Icon Set](http://led24.de/iconset/): .png icons make a professionally looking small icon set and are totally free in commercial and open source apps / websites.
- [Fugue Icons](http://p.yusukekamiyamane.com/): 3,480 icons are included in PNG format (16x16 pixels) + bonus. (CC license)

### Typography

- [Beautiful Web Type](http://hellohappy.org/beautiful-web-type/): A showcase of the best typefaces from the Google web fonts directory.
- [FontBomb](http://fontbomb.ilex.ca/): To blow up other websites, drag and drop this link fontBomb to your favorites bar

### Textures

- [Noise Texture Generator](http://www.noisetexturegenerator.com/)

#### Favicons

- [Piecon](http://lipka.github.com/piecon/): Pie charts in your favicon!

## Education

- [CodeAcademy](http://www.codecademy.com/): the easiest way to learn to code. It's interactive, fun, and you can do it with your friends.
- [NCZOnline: 'Computer Science'](http://www.nczonline.net/blog/tag/computer-science/): Nicholas C. Zakas presents computer science concepts using JavaScript as language of choice
- [Stanford OpenClassroom](http://openclassroom.stanford.edu/MainFolder/HomePage.php): Full courses. Short Videos. Free for everyone.
