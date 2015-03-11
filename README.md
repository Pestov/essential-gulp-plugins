[autoprefixer](https://github.com/postcss/autoprefixer) - parse CSS and add vendor prefixes to rules by Can I Use.

[gulp-browser-sync](https://github.com/BrowserSync/gulp-browser-sync) - keep multiple browsers & devices in sync when building websites.

[gulp-useref](https://github.com/jonkemp/gulp-useref) - parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets.

[gulp-email-design](https://github.com/alexshk/gulp-email-design) - a workflow for designing and testing HTML email templates.

[gulp-uncss](https://github.com/addyosmani/gulp-uncss-task) - remove unused CSS from your projects.

[gulp-csso](https://github.com/ben-eb/gulp-csso) - very cool CSS minificator. In addition, there are many CSS optimizers and [benchmark tests](http://goalsmashers.github.io/css-minification-benchmark/) ([GitHub](https://github.com/GoalSmashers/css-minification-benchmark)) for them. But recently I saw most powerful [Shorthand](https://github.com/frankmarineau/shorthand) utility without Gulp, which does folowing:

	a {
		font-family: Arial;
		font-style: italic;
		font-size: 14px;
		line-height: 18px; 
		font-weight: bold;
		background-image: url('example.png');
		background-color: red;
		background-size: cover;
		background-repeat: no-repeat;
	}
	
	=>
	
    a {
      font: italic bold 14px/18px Arial;
      background: red url('example.png') no-repeat / cover;
    }

[gulp-htmlmin](https://github.com/jonschlinkert/gulp-htmlmin) - neat HTML minificator. 

[gulp-csscomb](https://github.com/koistya/gulp-csscomb) - refines the structure of your CSS. 

[gulp-csslint](https://www.npmjs.com/package/gulp-csslint) - CSS linter. 

[gulp-htmlhint](https://github.com/bezoerb/gulp-htmlhint) - HTML validator.

##JavaScript
[gulp-autopolyfiller](https://github.com/azproduction/gulp-autopolyfiller) - precise polyfills. This is like Autoprefixer, but for JavaScript polyfills. 

[gulp-babel](https://github.com/babel/gulp-babel) - transpiler for writing next generation JavaScript.

[gulp-jsfmt](https://www.npmjs.com/package/gulp-jsfmt) - for formatting, searching, and rewriting JavaScript.

[gulp-jscs](https://github.com/jscs-dev/gulp-jscs) - for checking JavaScript Code Style. 

[gulp-modernizr](https://github.com/doctyper/gulp-modernizr) - build out a lean, mean Modernizr machine.

[gulp-express](https://github.com/gimm/gulp-express) — start (and supervise) an Express.js web server using, works well with socket.io 

[gulp-requirejs](https://github.com/robinthrift/gulp-requirejs) and [gulp-browserify](https://github.com/deepak1556/gulp-browserify) - optimize the work with RequireJS and Browserify respectively.

[gulp-plato](https://github.com/sindresorhus/gulp-plato) - generate static analysis reports.

[gulp-complexity](https://github.com/alexeyraspopov/gulp-complexity) - evaluates code maintainability using Halstead and Cyclomatic metrics.

[fixmyjs](https://github.com/kirjs/gulp-fixmyjs) - automatically fix silly lint errors with help of [JSHint](http://jshint.com/) ([gulp-jshint](https://github.com/spalger/gulp-jshint)).

[gulp-jscpd](https://github.com/yannickcr/gulp-jscpd) — copy/paste detector for programming source code.

[gulp-jsonlint](https://github.com/rogeriopvl/gulp-jsonlint)  - JSON validator.

[gulp-uglify](https://github.com/terinjokes/gulp-uglify) - JavaScript compressor. 

[gulp-concat](https://github.com/wearefractal/gulp-concat) - concatenate files. 

###Unit Tests
* [gulp-nodeunit](https://github.com/kjvalencik/gulp-nodeunit)
* [gulp-jasmine](https://github.com/sindresorhus/gulp-jasmine)
* [gulp-qunit](https://github.com/jonkemp/gulp-qunit)
* [gulp-mocha](https://github.com/sindresorhus/gulp-mocha)
* [gulp-karma](https://github.com/karma-runner/gulp-karma) 

##Graphics
[gulpicon](https://github.com/wakayama-io/gulpicon/) - mystical CSS icon solution.

[gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) - SVG to webfont converter.

[gulp-responsive](https://github.com/mahnunchik/gulp-responsive) - produce images at different sizes for responsive websites.

[gulp-sharp](https://github.com/rizalp/gulp-sharp) - fastest module for work JPEG, PNG, WebP and TIFF images.

[gulp-svgstore](https://github.com/w0rm/gulp-svgstore) - merge SVGs from a folder.

[gulp-imacss](https://github.com/akoenig/imacss) - application and library that transforms image files to data URIs.  

[gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin) и [gulp-tinypng](https://github.com/creativeaura/gulp-tinypng) or fimage compression. 

[gulp-spritesmith](https://github.com/otouto/gulp-spritesmith) - converting a set of images into a spritesheet and corresponding CSS variables.


##Others

[gulp-grunt](https://github.com/gratimax/gulp-grunt) - able to run Grunt tasks from Gulp.

[gulp-watch](https://github.com/floatdrop/gulp-watch) — run tasks whenever watched files change.

[gulp-notify](https://github.com/mikaelbr/gulp-notify) - automatic error messages in system notifications center when Gulp tasks fail.

[gulp-git](https://github.com/stevelacy/gulp-git) - able to use Git commands.

[gulp-jsdoc](https://github.com/jsBoot/gulp-jsdoc) - generate JavaScript documentation by running JSDoc3.

[gulp-rev](https://github.com/sindresorhus/gulp-rev) - static file asset revisioning through content hashing.

[gulp-release](https://github.com/pasangsherpa/gulp-release) - allows to manage versions of a project.

[gulp-bump](https://github.com/stevelacy/gulp-bump) - increments versions in package JSON and [gulp-update](https://github.com/tounano/gulp-update), which automatically updates packages.

[gulp-bower-files](https://github.com/ck86/gulp-bower-files) - inject Bower packages.

[gulp-removelogs](https://github.com/hemanth/gulp-removelogs) - remove console logging statements.

[gulp-preprocess](https://github.com/jas/gulp-preprocess) - preprocess files based off environment configuration. 

[gulp-duration](https://github.com/hughsk/gulp-duration) — displays the elapsed execution time of Gulp tasks.

[gulp-changed](https://github.com/sindresorhus/gulp-changed) and [gulp-newer](https://www.npmjs.com/package/gulp-newer) — run Gulp tasks with only those source files modified since the last successful run.

[gulp-connect](https://github.com/avevlad/gulp-connect) - simple static web server. 

[gulp-shell](https://github.com/sun-zheng-an/gulp-shell) - run Shell commands.

[gulp-ssh](https://github.com/teambition/gulp-ssh) - provides the ability to connect via SSH and SFTP.

[gulp-zip](https://www.npmjs.com/package/gulp-zip) - compress files and folders..

[gulp-clean](https://github.com/peter-vilja/gulp-clean) and [gulp-copy](https://github.com/klaascuvelier/gulp-copy) - respectively remove and copy sources. 

[gulp-filesize](https://github.com/Metrime/gulp-filesize) - displays sizes of files in a readable format.

[gulp-util](https://github.com/gulpjs/gulp-util) - utilities for developing Gulp plugins.

##Compilers
[gulp-less](https://github.com/plus3network/gulp-less) - LESS in CSS.
[gulp-sass](https://github.com/dlmanning/gulp-sass) - SASS/SCSS in СSS.
[gulp-compass](https://github.com/appleboy/gulp-compass) - SASS with Compass in CSS.
[gulp-stylus](https://github.com/LearnBoost/stylus) - Stylus in CSS.
[gulp-coffee](https://github.com/wearefractal/gulp-coffee) - CoffeeScript in JavaScript.
[gulp-jade](https://github.com/phated/gulp-jade) - Jade in HTML.
[gulp-handlebars](https://github.com/lazd/gulp-handlebars) - Handlebars templates in JST.
[gulp-jst](https://github.com/rdmurphy/gulp-jst) - Underscore templates in JST.
[gulp-react](https://github.com/sindresorhus/gulp-react) - Facebook React's JSX templates in JST.
[gulp-nunjucks](https://github.com/sindresorhus/gulp-nunjucks) - Nunjucks templates in JST. 
[gulp-dustjs](https://github.com/sindresorhus/gulp-dust) - Dust templates in JST.
[gulp-angular-templatecache](https://github.com/miickel/gulp-angular-templatecache) - AngularJS templates in JST.

##Finally
* [psi](https://github.com/addyosmani/psi) - PageSpeed Insights with reporting.
* [tmi](https://github.com/addyosmani/tmi) -  TMI (Too Many Images) - discover your image weight on the web.
* [ngrok](https://ngrok.com/) - Introspected tunnels to localhost.
* [pageres](https://github.com/sindresorhus/pageres) - responsive website screenshots.
* [matchdep](https://github.com/tkellen/node-matchdep) -  filter npm module dependencies.
* Maybe some automatization methods you want to use directly in the editor, so look at the [The Best Plugins for Sublime Text](http://ipestov.com/the-best-plugins-for-sublime-text/). 
