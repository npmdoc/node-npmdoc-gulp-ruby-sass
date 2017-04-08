# api documentation for  [gulp-ruby-sass (v2.1.1)](https://github.com/sindresorhus/gulp-ruby-sass#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-ruby-sass.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-ruby-sass) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-ruby-sass.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-ruby-sass)
#### Compile Sass to CSS with Ruby Sass

[![NPM](https://nodei.co/npm/gulp-ruby-sass.png?downloads=true)](https://www.npmjs.com/package/gulp-ruby-sass)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-gulp-ruby-sass%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/sindresorhus/gulp-ruby-sass/issues"
    },
    "dependencies": {
        "convert-source-map": "^1.0.0",
        "cross-spawn": "^5.0.0",
        "dargs": "^2.0.3",
        "each-async": "^1.0.0",
        "escape-string-regexp": "^1.0.3",
        "glob": "^7.0.3",
        "glob2base": "0.0.12",
        "gulp-util": "^3.0.4",
        "md5-hex": "^1.0.2",
        "object-assign": "^4.0.1",
        "os-tmpdir": "^1.0.0",
        "path-exists": "^2.0.0",
        "rimraf": "^2.2.8"
    },
    "description": "Compile Sass to CSS with Ruby Sass",
    "devDependencies": {
        "gulp": "^3.8.11",
        "gulp-sourcemaps": "^2.2.0",
        "mocha": "*",
        "vinyl-file": "^2.0.0",
        "xo": "^0.16.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e80f65092108ee4afcb4936088dc7253369adcac",
        "tarball": "https://registry.npmjs.org/gulp-ruby-sass/-/gulp-ruby-sass-2.1.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "be9483b804d67aa3b71e38f387b4bba65bcf2d3b",
    "homepage": "https://github.com/sindresorhus/gulp-ruby-sass#readme",
    "keywords": [
        "gulpplugin",
        "scss",
        "sass",
        "css",
        "compile",
        "preprocessor",
        "style",
        "ruby",
        "source-map",
        "source-maps",
        "sourcemap",
        "sourcemaps"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "robwierzbowski",
            "email": "hello@robwierzbowski.com"
        }
    ],
    "name": "gulp-ruby-sass",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/gulp-ruby-sass.git"
    },
    "scripts": {
        "test": "xo && cd test && mocha test.js"
    },
    "version": "2.1.1",
    "xo": {
        "rules": {
            "brace-style": [
                "error",
                "stroustrup",
                {
                    "allowSingleLine": false
                }
            ]
        }
    }
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-ruby-sass](#apidoc.module.gulp-ruby-sass)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.</span>clearCache (tempDir)](#apidoc.element.gulp-ruby-sass.clearCache)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.</span>logError (err)](#apidoc.element.gulp-ruby-sass.logError)
1.  object <span class="apidocSignatureSpan">gulp-ruby-sass.</span>logger
1.  object <span class="apidocSignatureSpan">gulp-ruby-sass.</span>utils

#### [module gulp-ruby-sass.logger](#apidoc.module.gulp-ruby-sass.logger)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>error (stream, err)](#apidoc.element.gulp-ruby-sass.logger.error)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>prettifyDirectoryLogging (msg, intermediateDir)](#apidoc.element.gulp-ruby-sass.logger.prettifyDirectoryLogging)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>stderr (stream, intermediateDir, data)](#apidoc.element.gulp-ruby-sass.logger.stderr)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>stdout (stream, intermediateDir, data)](#apidoc.element.gulp-ruby-sass.logger.stdout)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>verbose (command, args)](#apidoc.element.gulp-ruby-sass.logger.verbose)

#### [module gulp-ruby-sass.utils](#apidoc.module.gulp-ruby-sass.utils)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.utils.</span>calculateBase (source)](#apidoc.element.gulp-ruby-sass.utils.calculateBase)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.utils.</span>createIntermediatePath (sources, matches, options)](#apidoc.element.gulp-ruby-sass.utils.createIntermediatePath)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.utils.</span>emitErr (stream, err)](#apidoc.element.gulp-ruby-sass.utils.emitErr)
1.  [function <span class="apidocSignatureSpan">gulp-ruby-sass.utils.</span>replaceLocation (origPath, currentLoc, newLoc)](#apidoc.element.gulp-ruby-sass.utils.replaceLocation)



# <a name="apidoc.module.gulp-ruby-sass"></a>[module gulp-ruby-sass](#apidoc.module.gulp-ruby-sass)

#### <a name="apidoc.element.gulp-ruby-sass.clearCache"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.</span>clearCache (tempDir)](#apidoc.element.gulp-ruby-sass.clearCache)
- description and source-code
```javascript
clearCache = function (tempDir) {
	tempDir = tempDir || defaults.tempDir;
	rimraf.sync(tempDir);
}
```
- example usage
```shell
...
);
'''

### sass.logError(err)

Convenience function for pretty error logging.

### sass.clearCache([tempDir])

In rare cases you may need to clear gulp-ruby-sass's cache. This sync function deletes all files used for Sass caching. If you've
 set a custom temporary directory in your task you must pass it to 'clearCache'.


## Issues

This plugin wraps the Sass gem for the gulp build system. It does not alter Sass's output in any way. Any issues with Sass output
 should be reported to the [Sass issue tracker](https://github.com/sass/sass/issues).
...
```

#### <a name="apidoc.element.gulp-ruby-sass.logError"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.</span>logError (err)](#apidoc.element.gulp-ruby-sass.logError)
- description and source-code
```javascript
logError = function (err) {
	var message = new gutil.PluginError('gulp-ruby-sass', err);
	process.stderr.write(message + '\n');
	this.emit('end');
}
```
- example usage
```shell
...
			loadPath: [ 'library', '../../shared-components' ]
		})
		.on('error', sass.logError)
		.pipe(gulp.dest('result'))
);
'''

### sass.logError(err)

Convenience function for pretty error logging.

### sass.clearCache([tempDir])

In rare cases you may need to clear gulp-ruby-sass's cache. This sync function deletes all files used for Sass caching. If you've
 set a custom temporary directory in your task you must pass it to 'clearCache'.
...
```



# <a name="apidoc.module.gulp-ruby-sass.logger"></a>[module gulp-ruby-sass.logger](#apidoc.module.gulp-ruby-sass.logger)

#### <a name="apidoc.element.gulp-ruby-sass.logger.error"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>error (stream, err)](#apidoc.element.gulp-ruby-sass.logger.error)
- description and source-code
```javascript
error = function (stream, err) {
	if (err.code === 'ENOENT') {
		// Spawn error: gems not installed
		emitErr(stream, 'Gem ' + err.path + ' is not installed.');
	}
	else {
		// Other errors
		emitErr(stream, err);
	}
}
```
- example usage
```shell
...
	});

	sass.stderr.on('data', function (data) {
		logger.stderr(stream, intermediateDir, data);
	});

	sass.on('error', function (err) {
		logger.error(stream, err);
	});

	sass.on('close', function (code) {
		if (options.emitCompileError && code !== 0) {
			emitErr(stream, 'Sass compilation failed. See console output for more information.');
		}
...
```

#### <a name="apidoc.element.gulp-ruby-sass.logger.prettifyDirectoryLogging"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>prettifyDirectoryLogging (msg, intermediateDir)](#apidoc.element.gulp-ruby-sass.logger.prettifyDirectoryLogging)
- description and source-code
```javascript
prettifyDirectoryLogging = function (msg, intermediateDir) {
	var escapedDir = escapeStringRegexp(intermediateDir);
	return msg.replace(new RegExp(escapedDir + '/?', 'g'), './');
}
```
- example usage
```shell
...
	}
	// Sass error: directory missing
	else if (/No such file or directory @ rb_sysopen/.test(data)) {
		emitErr(stream, data.trim());
	}
	// Not an error: Sass logging
	else {
		data = logger.prettifyDirectoryLogging(data, intermediateDir);
		data = data.trim();
		gutil.log(data);
	}
};

logger.stderr = function (stream, intermediateDir, data) {
	var bundlerMissing = /Could not find 'bundler' \((.*?)\)/.exec(data);
...
```

#### <a name="apidoc.element.gulp-ruby-sass.logger.stderr"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>stderr (stream, intermediateDir, data)](#apidoc.element.gulp-ruby-sass.logger.stderr)
- description and source-code
```javascript
stderr = function (stream, intermediateDir, data) {
	var bundlerMissing = /Could not find 'bundler' \((.*?)\)/.exec(data);
	var sassVersionMissing = /Could not find gem 'sass \((.*?)\) ruby'/.exec(data);

	// Ruby error: Bundler gem not installed
	if (bundlerMissing) {
		emitErr(stream, 'ruby: Could not find \'bundler\' (' + bundlerMissing[1] + ').');
	}
	// Bundler error: no matching Sass version
	else if (sassVersionMissing) {
		emitErr(stream, 'bundler: Could not find gem \'sass (' + sassVersionMissing[1] + ')\'.');
	}
	// Sass error: file missing
	else if (/No such file or directory @ rb_sysopen/.test(data)) {
		emitErr(stream, data.trim());
	}
	// Not an error: Sass warnings, debug statements
	else {
		data = logger.prettifyDirectoryLogging(data, intermediateDir);
		data = data.trim();
		gutil.log(data);
	}
}
```
- example usage
```shell
...
	sass.stderr.setEncoding('utf8');

	sass.stdout.on('data', function (data) {
		logger.stdout(stream, intermediateDir, data);
	});

	sass.stderr.on('data', function (data) {
		logger.stderr(stream, intermediateDir, data);
	});

	sass.on('error', function (err) {
		logger.error(stream, err);
	});

	sass.on('close', function (code) {
...
```

#### <a name="apidoc.element.gulp-ruby-sass.logger.stdout"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>stdout (stream, intermediateDir, data)](#apidoc.element.gulp-ruby-sass.logger.stdout)
- description and source-code
```javascript
stdout = function (stream, intermediateDir, data) {
	// Bundler error: no Sass version found
	if (/bundler: command not found: sass/.test(data)) {
		emitErr(stream, 'bundler: command not found: sass');
	}
	// Bundler error: Gemfile not found
	else if (/Could not locate Gemfile or .bundle\/ directory/.test(data)) {
		emitErr(stream, 'bundler: could not locate Gemfile or .bundle directory');
	}
	// Sass error: directory missing
	else if (/No such file or directory @ rb_sysopen/.test(data)) {
		emitErr(stream, data.trim());
	}
	// Not an error: Sass logging
	else {
		data = logger.prettifyDirectoryLogging(data, intermediateDir);
		data = data.trim();
		gutil.log(data);
	}
}
```
- example usage
```shell
...

	var sass = spawn(command, args);

	sass.stdout.setEncoding('utf8');
	sass.stderr.setEncoding('utf8');

	sass.stdout.on('data', function (data) {
		logger.stdout(stream, intermediateDir, data);
	});

	sass.stderr.on('data', function (data) {
		logger.stderr(stream, intermediateDir, data);
	});

	sass.on('error', function (err) {
...
```

#### <a name="apidoc.element.gulp-ruby-sass.logger.verbose"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.logger.</span>verbose (command, args)](#apidoc.element.gulp-ruby-sass.logger.verbose)
- description and source-code
```javascript
verbose = function (command, args) {
	gutil.log('Running command ' + command + ' ' + args.join(' '));
}
```
- example usage
```shell
...
	}
	else {
		command = 'sass';
	}

	// plugin logging
	if (options.verbose) {
		logger.verbose(command, args);
	}

	var sass = spawn(command, args);

	sass.stdout.setEncoding('utf8');
	sass.stderr.setEncoding('utf8');
...
```



# <a name="apidoc.module.gulp-ruby-sass.utils"></a>[module gulp-ruby-sass.utils](#apidoc.module.gulp-ruby-sass.utils)

#### <a name="apidoc.element.gulp-ruby-sass.utils.calculateBase"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.utils.</span>calculateBase (source)](#apidoc.element.gulp-ruby-sass.utils.calculateBase)
- description and source-code
```javascript
calculateBase = function (source) {
	return glob2base(new glob.Glob(source));
}
```
- example usage
```shell
...
	}

	var matches = [];
	var bases = [];

	sources.forEach(function (source) {
		matches.push(glob.sync(source));
		bases.push(options.base || utils.calculateBase(source));
	});

	// log and return stream if there are no file matches
	if (matches[0].length < 1) {
		gutil.log('No files matched your Sass source.');
		stream.push(null);
		return stream;
...
```

#### <a name="apidoc.element.gulp-ruby-sass.utils.createIntermediatePath"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.utils.</span>createIntermediatePath (sources, matches, options)](#apidoc.element.gulp-ruby-sass.utils.createIntermediatePath)
- description and source-code
```javascript
createIntermediatePath = function (sources, matches, options) {
	return path.join(
		options.tempDir,
		md5Hex(
			process.cwd() +
			JSON.stringify(sources) +
			JSON.stringify(matches) +
			JSON.stringify(options)
		)
	);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-ruby-sass.utils.emitErr"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.utils.</span>emitErr (stream, err)](#apidoc.element.gulp-ruby-sass.utils.emitErr)
- description and source-code
```javascript
emitErr = function (stream, err) {
	stream.emit('error', new gutil.PluginError('gulp-ruby-sass', err));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-ruby-sass.utils.replaceLocation"></a>[function <span class="apidocSignatureSpan">gulp-ruby-sass.utils.</span>replaceLocation (origPath, currentLoc, newLoc)](#apidoc.element.gulp-ruby-sass.utils.replaceLocation)
- description and source-code
```javascript
replaceLocation = function (origPath, currentLoc, newLoc) {
	return path.join(
		newLoc,
		path.relative(currentLoc, origPath)
	);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
