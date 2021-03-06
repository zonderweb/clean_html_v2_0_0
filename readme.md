<h1>OptimizedHTML (Scss) - v2.0.1 + Addons</h1>

<p>
	<img src="https://raw.githubusercontent.com/zonderweb/clean_html_v2_0_0/master/app/img/prew_html_2.jpg" alt="Start HTML Template">
</p>

<p><a href="http://webdesign-master.ru/blog/tools/2016-08-19-optimizedhtml.html" target="_blank">Manual in Russian</a></p>

<p>OptimizedHTML is all-inclusive, optimized for Google PageSpeed start HTML5 template with Bootstrap (grid only), Gulp, Sass, Browsersync, Autoprefixer, Clean-CSS, Uglify, Imagemin, Vinyl-FTP, Bower (libs path). The template contains a <strong>.htaccess</strong> file with caching rules for web server.</p>

<p>Addons: <strong>Susy</strong>, <strong>OWL.Carousel</strong>, <strong>FontAwesome</strong>, <strong>normalize.css</strong>, <strong>magnific-popup</strong>, <strong>JQ-Easy-Tabs</strong>.</p>

<p>OptimizedHTML Start Template uses the best practices of web development and optimized for Google PageSpeed.</p>

<p>Cross-browser compatibility: IE9+.</p>

<p>The template uses a Sass with <strong>Scss</strong> syntax and project structure with source code in the directory <strong>app/</strong> and production folder <strong>dist/</strong>, that contains ready project with optimized HTML, CSS, JS and images.</p>

<h2>How to use OptimizedHTML</h2>

<ol>
	<li><a href="https://github.com/zonderweb/clean_html_v2_0_0/archive/master.zip">Download</a> <strong>optimizedhtml-start-template</strong> from GitHub <br> or <strong>git clone https://github.com/zonderweb/clean_html_v2_0_1.git</strong>;</li>
	<li>update node modules: <strong>npm ncu</strong>;</li>
	<li>Install Node Modules: <strong>npm i</strong>;</li>
	<li>Run the template: <strong>gulp</strong>.</li>
</ol>

<h2>Gulp tasks:</h2>

<ul>
	<li><strong>gulp</strong>: run default gulp task (sass, js, watch, browserSync) for web development;</li>
	<li><strong>build</strong>: build project to <strong>dist</strong> folder (cleanup, image optimize, removing unnecessary files);</li>
	<li><strong>deploy</strong>: project deployment on the server from <strong>dist</strong> folder via FTP;</li>
	<li><strong>clearcache</strong>: clear all gulp cache.</li>
</ul>

<h2>Rules for working with the starting HTML template</h2>

<ol>
	<li>All HTML files should have similar initial content as in <strong>app/index.html</strong>;</li>
	<li><strong>Template Basic Images Start</strong> comment in app/index.html - all your custom template basic images (og:image for social networking, favicons for a variety of devices);</li>
	<li><strong>Custom Browsers Color Start</strong> comment in app/index.html: set the color of the browser head on a variety of devices;</li>
	<li><strong>Custom HTML</strong> comment in app/index.html - all your custom HTML;</li>
	<li>For installing new jQuery library, just run the command "<strong>bower i plugin-name</strong>" in the terminal. Libraries are automatically placed in the folder <strong>app/libs</strong>. Bower must be installed in the system (npm i -g bower). Then place all jQuery libraries paths in the <strong>'libs'</strong> task (gulpfile.js);</li>
	<li>All custom JS located in <strong>app/js/common.js</strong>;</li>
	<li>All Sass vars placed in <strong>app/sass/_vars.scss</strong>;</li>
	<li>All Bootstrap media queries placed in <strong>app/sass/_media.scss</strong>;</li>
	<li>All jQuery libraries CSS styles placed in <strong>app/sass/_libs.scss</strong>;</li>
	<li>Rename <strong>ht.access</strong> to <strong>.htaccess</strong> before place it in your web server. This file contain rules for files caching on web server.</li>
</ol>
