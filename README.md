# api documentation for  [traceur (v0.0.111)](https://github.com/google/traceur-compiler)  [![npm package](https://img.shields.io/npm/v/npmdoc-traceur.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-traceur) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-traceur.svg)](https://travis-ci.org/npmdoc/node-npmdoc-traceur)
#### ES6 to ES5 compiler

[![NPM](https://nodei.co/npm/traceur.png?downloads=true)](https://www.npmjs.com/package/traceur)

[![apidoc](https://npmdoc.github.io/node-npmdoc-traceur/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-traceur_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-traceur/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-traceur/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-traceur/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Traceur Authors"
    },
    "bin": {
        "traceur": "./traceur"
    },
    "bugs": {
        "url": "https://github.com/google/traceur-compiler/issues"
    },
    "contributors": [
        {
            "name": "The Chromium Authors",
            "email": "*@chromium.org"
        },
        {
            "name": "Google Inc.",
            "email": "*@google.com"
        },
        {
            "name": "Viktor Kronvall",
            "email": "viktor.kronvall@gmail.com"
        },
        {
            "name": "Ben Chan",
            "email": "usrbincc@yahoo.com"
        },
        {
            "name": "Eduard Burtescu",
            "email": "edy.burt@gmail.com"
        },
        {
            "name": "Peter Hallam",
            "email": "peter@peterhallam.com"
        },
        {
            "name": "Nick Schonning",
            "email": "nschonni@gmail.com"
        },
        {
            "name": "Kinya TERASAKA",
            "email": "terasaka.k@gmail.com"
        },
        {
            "name": "Sean Middleditch",
            "email": "sean@seanmiddleditch.com"
        },
        {
            "name": "Ross Hadden",
            "email": "ross@rhadden.com"
        },
        {
            "name": "Stephan Seidt",
            "email": "stephan.seidt@gmail.com"
        },
        {
            "name": "Mathias Bynens",
            "email": "mathias@qiwi.be"
        },
        {
            "name": "Tommy Odom",
            "email": "tommy.odom@gmail.com"
        },
        {
            "name": "Rolf Timmermans",
            "email": "r.w.timmermans@gmail.com"
        },
        {
            "name": "Tomi Belan",
            "email": "tomi.belan@gmail.com"
        },
        {
            "name": "James Lal",
            "email": "james@lightsofapollo.com"
        },
        {
            "name": "Galimzyanov Dmitry",
            "email": "dmt021@gmail.com"
        },
        {
            "name": "Rick Waldron",
            "email": "waldron.rick@gmail.com"
        },
        {
            "name": "A. Matías Quezada",
            "email": "amatiasq@gmail.com"
        },
        {
            "name": "Sam Day",
            "email": "sday@atlassian.com"
        },
        {
            "name": "Guy Bedford",
            "email": "guybedford@gmail.com"
        },
        {
            "name": "Jeff McRiffey",
            "email": "jmcriffey@gmail.com"
        },
        {
            "name": "Marius Nita",
            "email": "m@mariusnita.com"
        },
        {
            "name": "Nick Fitzgerald",
            "email": "fitzgen@mozilla.com"
        },
        {
            "name": "Gil Tayar",
            "email": "gil@tayar.org"
        },
        {
            "name": "Aleksander Heintz",
            "email": "alxandr@alxandr.me"
        },
        {
            "name": "Ulrik de Muelenaere",
            "email": "ulrikdem@gmail.com"
        },
        {
            "name": "Maël Nison",
            "email": "nison.mael@gmail.com"
        },
        {
            "name": "Shinnosuke Watanabe",
            "email": "snnskwtnb@gmail.com"
        },
        {
            "name": "Vyacheslav Shebanov",
            "email": "terminal2010@gmail.com"
        },
        {
            "name": "Fabrício Matté",
            "email": "ultcombo@gmail.com"
        },
        {
            "name": "Jordan Harband",
            "email": "ljharb@gmail.com"
        },
        {
            "name": "Martín Ciparelli",
            "email": "mciparelli@gmail.com"
        },
        {
            "name": "David Håsäther",
            "email": "hasather@gmail.com"
        },
        {
            "name": "Amjad Masad",
            "email": "amjad.masad@gmail.com"
        },
        {
            "name": "Peter Flannery",
            "email": "flannery.peter@ntlworld.com"
        },
        {
            "name": "Liubomyr Mykhalchenko",
            "email": "liubko.qwert@gmail.com"
        },
        {
            "name": "Dmitry Soshnikov",
            "email": "dmitry.soshnikov@gmail.com"
        },
        {
            "name": "Victor Berchet",
            "email": "victor@suumit.com"
        },
        {
            "name": "Paul Selden",
            "email": "pselden4@gmail.com"
        },
        {
            "name": "Steven Vachon",
            "email": "contact@svachon.com"
        },
        {
            "name": "Maga D. Zandaqo",
            "email": "denelxan@gmail.com"
        },
        {
            "name": "Valeriy Sorokobatko",
            "email": "valeriy.sorokobatko@gmail.com"
        },
        {
            "name": "Ivan Willig",
            "email": "iwillig@gmail.com"
        },
        {
            "name": "Oliver Joseph Ash",
            "email": "oliverjash@gmail.com"
        },
        {
            "name": "Chris Truter",
            "email": "jeffpalentine@gmail.com"
        },
        {
            "name": "Marc Nieper-Wißkirchen",
            "email": "marc.nieper@gmail.com"
        },
        {
            "name": "Rogério Yokomizo",
            "email": "me@ro.ger.io"
        },
        {
            "name": "Caitlin Potter",
            "email": "caitpotter88@gmail.com"
        },
        {
            "name": "Srinivasan Sekar",
            "email": "srinivasan.sekar1990@gmail.com"
        },
        {
            "name": "Jeff Shen",
            "email": "jeffshen86@gmail.com"
        },
        {
            "name": "Erik Arvidsson",
            "email": "erik.arvidsson@gmail.com"
        }
    ],
    "dependencies": {
        "commander": "2.9.x",
        "glob": "5.0.x",
        "rsvp": "^3.0.13",
        "semver": "^4.3.3",
        "source-map-support": "~0.2.8"
    },
    "description": "ES6 to ES5 compiler",
    "devDependencies": {
        "chai": "2.2.x",
        "express": "4.x",
        "mocha": "2.2.x",
        "node-uuid": "1.x",
        "promises-aplus-tests": "2.x",
        "regenerate": "1.2.1",
        "regexpu": "1.1.0",
        "regjsgen": "0.2.0",
        "regjsparser": "0.1.5",
        "requirejs": "2.x",
        "serve-index": "1.x",
        "source-map": "0.1.43",
        "traceur": "0.0.110",
        "webcomponents.js": "^0.5.4-1"
    },
    "directories": {},
    "dist": {
        "shasum": "c04de74d14696c3373427de4fc08ecaf913fc3a1",
        "tarball": "https://registry.npmjs.org/traceur/-/traceur-0.0.111.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "bin/traceur.js",
        "bin/traceur.js.map",
        "bin/traceur-runtime.js",
        "bin/BrowserSystem.js",
        "src/",
        "dist/",
        "traceur"
    ],
    "gitHead": "2ddade7061e895b7dddb56ed4b89df310386860b",
    "homepage": "https://github.com/google/traceur-compiler",
    "keywords": [
        "javascript",
        "ecmascript",
        "language",
        "es5",
        "es6",
        "ES.next",
        "harmony",
        "compiler",
        "transpiler"
    ],
    "license": "Apache-2.0",
    "main": "./src/node/api.js",
    "maintainers": [
        {
            "name": "arv",
            "email": "arv@chromium.org"
        },
        {
            "name": "johnjbarton",
            "email": "johnjbarton@johnjbarton.com"
        }
    ],
    "name": "traceur",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/google/traceur-compiler.git"
    },
    "scripts": {
        "/** Update Version Number **/": "After publishing version N, update the version number and commit the result",
        "/** Update gh-pages branch **/": "Ater publishing version N, update the github docs and REPL",
        "checkout-gh-pages": "git checkout -b upstream_gh_pages upstream/master",
        "checkout-upstream": "git checkout -b upstream_master upstream/master",
        "commit-gh-pages": "git add -- src/ bin/ && ./traceur -v | xargs -I VERSION git commit -a -m \"Commit binaries for VERSION\"",
        "commit-published": "cat build/npm-version-number | xargs -I VERSION git commit -a -m \"VERSION\"",
        "just-publish": "npm publish # workaround https://github.com/npm/npm/issues/10074 ",
        "postjust-publish": "npm run push-published && npm run push-gh-pages",
        "postpush-gh-pages": "git checkout master && git branch -D upstream_gh_pages",
        "postpush-published": "git checkout master && git branch -D upstream_master",
        "precheckout-gh-pages": "git branch -D upstream_gh_pages || true",
        "precheckout-upstream": "git fetch upstream && git branch -D upstream_master || true",
        "precommit-gh-pages": "npm run checkout-gh-pages && npm run rebuild && cp gh-pages.gitignore .gitignore # tell git to commit built files.",
        "precommit-published": "npm run update-semver && npm run rebuild",
        "prejust-publish": "npm run checkout-upstream && npm run rebuild",
        "prepush-gh-pages": "npm run commit-gh-pages",
        "prepush-published": "npm run commit-published && npm run tag-published",
        "push-gh-pages": "git push -f upstream upstream_gh_pages:gh-pages",
        "push-published": "git push --tags upstream upstream_master:master && git push upstream upstream_master:master  # Push source for version N+1",
        "rebuild": "make clean && make dist/commonjs && make test",
        "start": "make && node ./demo/expressServer.js",
        "store-semver": "node build/versionInfo.js -v > build/npm-version-number",
        "tag-published": "cat build/npm-version-number | xargs -I VERSION git tag -a VERSION -m \"Tagged version VERSION \"",
        "test": "make test",
        "update-semver": "npm run store-semver && git diff --quiet -- package.json && node build/versionInfo.js -n"
    },
    "subdomain": "traceur",
    "version": "0.0.111"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module traceur](#apidoc.module.traceur)
1.  [function <span class="apidocSignatureSpan">traceur.</span>NodeCompiler (options, sourceRoot)](#apidoc.element.traceur.NodeCompiler)
1.  [function <span class="apidocSignatureSpan">traceur.</span>amdOptions ()](#apidoc.element.traceur.amdOptions)
1.  [function <span class="apidocSignatureSpan">traceur.</span>closureOptions ()](#apidoc.element.traceur.closureOptions)
1.  [function <span class="apidocSignatureSpan">traceur.</span>commonJSOptions ()](#apidoc.element.traceur.commonJSOptions)
1.  [function <span class="apidocSignatureSpan">traceur.</span>compile (src, options, sourceName, outputName)](#apidoc.element.traceur.compile)
1.  [function <span class="apidocSignatureSpan">traceur.</span>compileAllJsFilesInDir (inputDir, outputDir, options)](#apidoc.element.traceur.compileAllJsFilesInDir)
1.  [function <span class="apidocSignatureSpan">traceur.</span>forEachRecursiveModuleCompile (outputDir, includes, options)](#apidoc.element.traceur.forEachRecursiveModuleCompile)
1.  [function <span class="apidocSignatureSpan">traceur.</span>recursiveModuleCompileToSingleFile (outputFile, includes, options)](#apidoc.element.traceur.recursiveModuleCompileToSingleFile)
1.  object <span class="apidocSignatureSpan">traceur.</span>NodeCompiler.prototype
1.  string <span class="apidocSignatureSpan">traceur.</span>RUNTIME_PATH

#### [module traceur.NodeCompiler](#apidoc.module.traceur.NodeCompiler)
1.  [function <span class="apidocSignatureSpan">traceur.</span>NodeCompiler (options, sourceRoot)](#apidoc.element.traceur.NodeCompiler.NodeCompiler)

#### [module traceur.NodeCompiler.prototype](#apidoc.module.traceur.NodeCompiler.prototype)
1.  [function <span class="apidocSignatureSpan">traceur.NodeCompiler.prototype.</span>compileSingleFile (inputFilePath, outputFilePath, errback)](#apidoc.element.traceur.NodeCompiler.prototype.compileSingleFile)
1.  [function <span class="apidocSignatureSpan">traceur.NodeCompiler.prototype.</span>sourceMappingURL (filename)](#apidoc.element.traceur.NodeCompiler.prototype.sourceMappingURL)
1.  [function <span class="apidocSignatureSpan">traceur.NodeCompiler.prototype.</span>writeTreeToFile (tree, filename)](#apidoc.element.traceur.NodeCompiler.prototype.writeTreeToFile)



# <a name="apidoc.module.traceur"></a>[module traceur](#apidoc.module.traceur)

#### <a name="apidoc.element.traceur.NodeCompiler"></a>[function <span class="apidocSignatureSpan">traceur.</span>NodeCompiler (options, sourceRoot)](#apidoc.element.traceur.NodeCompiler)
- description and source-code
```javascript
function NodeCompiler(options, sourceRoot) {
  sourceRoot = sourceRoot || process.cwd();
  Compiler.call(this, options, sourceRoot);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.amdOptions"></a>[function <span class="apidocSignatureSpan">traceur.</span>amdOptions ()](#apidoc.element.traceur.amdOptions)
- description and source-code
```javascript
amdOptions = function () {
  var options = arguments[0] !== (void 0) ? arguments[0] : {};
  var amdOptions = {
    modules: 'amd',
    sourceMaps: false,
    moduleName: false
  };
  return merge(amdOptions, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.closureOptions"></a>[function <span class="apidocSignatureSpan">traceur.</span>closureOptions ()](#apidoc.element.traceur.closureOptions)
- description and source-code
```javascript
closureOptions = function () {
  var options = arguments[0] !== (void 0) ? arguments[0] : {};
  var closureOptions = {
    modules: 'closure',
    sourceMaps: false,
    moduleName: true
  };
  return merge(closureOptions, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.commonJSOptions"></a>[function <span class="apidocSignatureSpan">traceur.</span>commonJSOptions ()](#apidoc.element.traceur.commonJSOptions)
- description and source-code
```javascript
commonJSOptions = function () {
  var options = arguments[0] !== (void 0) ? arguments[0] : {};
  var commonjsOptions = {
    modules: 'commonjs',
    sourceMaps: false,
    moduleName: false
  };
  return merge(commonjsOptions, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.compile"></a>[function <span class="apidocSignatureSpan">traceur.</span>compile (src, options, sourceName, outputName)](#apidoc.element.traceur.compile)
- description and source-code
```javascript
function compile(src, options, sourceName, outputName) {
  sourceName = sourceName || '<compile-source>';
  outputName = outputName || '<compile-output>';
  return new NodeCompiler(Compiler.commonJSOptions(options)).
      compile(src, sourceName, outputName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.compileAllJsFilesInDir"></a>[function <span class="apidocSignatureSpan">traceur.</span>compileAllJsFilesInDir (inputDir, outputDir, options)](#apidoc.element.traceur.compileAllJsFilesInDir)
- description and source-code
```javascript
function compileAllJsFilesInDir(inputDir, outputDir, options) {
  inputDir = path.normalize(inputDir).replace(/\\/g, '/');
  outputDir = path.normalize(outputDir).replace(/\\/g, '/');
  glob(inputDir + '/**/*.js', {}, function (er, files) {
    if (er)
      throw new Error('While scanning ' + inputDir + ': ' + er);

    files.forEach(function(inputFilePath) {
      var outputFilePath = inputFilePath.replace(inputDir, outputDir);
      var compiler = new NodeCompiler(options);
      compiler.compileSingleFile(inputFilePath, outputFilePath, function(err) {
        throw new Error('While reading ' + inputFilePath + ': ' + err);
      });
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.forEachRecursiveModuleCompile"></a>[function <span class="apidocSignatureSpan">traceur.</span>forEachRecursiveModuleCompile (outputDir, includes, options)](#apidoc.element.traceur.forEachRecursiveModuleCompile)
- description and source-code
```javascript
function forEachRecursiveModuleCompile(outputDir, includes, options) {
  var outputDir = path.resolve(outputDir);
  var compiler = new NodeCompiler(options);
  function getPromise (input) {
    return recursiveModuleCompile([input], options).then(function(tree) {
      var outputFileName = path.join(outputDir, input.name);
      compiler.writeTreeToFile(tree, outputFileName);
    });
  }
  return Promise.all(includes.map(getPromise));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.recursiveModuleCompileToSingleFile"></a>[function <span class="apidocSignatureSpan">traceur.</span>recursiveModuleCompileToSingleFile (outputFile, includes, options)](#apidoc.element.traceur.recursiveModuleCompileToSingleFile)
- description and source-code
```javascript
function recursiveModuleCompileToSingleFile(outputFile, includes, options) {
  var resolvedOutputFile = path.resolve(outputFile);
  var outputDir = path.dirname(resolvedOutputFile);

  // Resolve includes before changing directory.
  var resolvedIncludes = includes.map(function(include) {
    include.name = path.resolve(include.name);
    include.rootModule = true;
    return include;
  });

  options.bundle = includes.length > 1;
  var compiler = new NodeCompiler(options);

  mkdirRecursive(outputDir);
  process.chdir(outputDir);
  // Make includes relative to output dir so that sourcemap paths are correct.
  resolvedIncludes = resolvedIncludes.map(function(include) {
    include.name = normalizePath(path.relative(outputDir, include.name));
    return include;
  });

  return recursiveModuleCompile(resolvedIncludes, options)
      .then(function(tree) {
        compiler.writeTreeToFile(tree, resolvedOutputFile);
      }).then(revertCwd, function(err) {
        revertCwd();
        throw err;
      });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.traceur.NodeCompiler"></a>[module traceur.NodeCompiler](#apidoc.module.traceur.NodeCompiler)

#### <a name="apidoc.element.traceur.NodeCompiler.NodeCompiler"></a>[function <span class="apidocSignatureSpan">traceur.</span>NodeCompiler (options, sourceRoot)](#apidoc.element.traceur.NodeCompiler.NodeCompiler)
- description and source-code
```javascript
function NodeCompiler(options, sourceRoot) {
  sourceRoot = sourceRoot || process.cwd();
  Compiler.call(this, options, sourceRoot);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.traceur.NodeCompiler.prototype"></a>[module traceur.NodeCompiler.prototype](#apidoc.module.traceur.NodeCompiler.prototype)

#### <a name="apidoc.element.traceur.NodeCompiler.prototype.compileSingleFile"></a>[function <span class="apidocSignatureSpan">traceur.NodeCompiler.prototype.</span>compileSingleFile (inputFilePath, outputFilePath, errback)](#apidoc.element.traceur.NodeCompiler.prototype.compileSingleFile)
- description and source-code
```javascript
compileSingleFile = function (inputFilePath, outputFilePath, errback) {
  inputFilePath = this.normalize(inputFilePath);
  outputFilePath = this.normalize(outputFilePath);
  fs.readFile(inputFilePath, function(err, contents) {
    if (err) {
      errback(err);
      return;
    }

    var parsed = this.parse(contents.toString(), inputFilePath);
    this.writeTreeToFile(this.transform(parsed, inputFilePath),
                         outputFilePath);
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.NodeCompiler.prototype.sourceMappingURL"></a>[function <span class="apidocSignatureSpan">traceur.NodeCompiler.prototype.</span>sourceMappingURL (filename)](#apidoc.element.traceur.NodeCompiler.prototype.sourceMappingURL)
- description and source-code
```javascript
sourceMappingURL = function (filename) {
  if (this.options_.sourceMaps === 'inline') {
    var base64sm = new Buffer(this.getSourceMap()).toString('base64');
    return 'data:application/json;base64,' + base64sm;
  }
  return Compiler.prototype.sourceMappingURL.call(this, filename);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.traceur.NodeCompiler.prototype.writeTreeToFile"></a>[function <span class="apidocSignatureSpan">traceur.NodeCompiler.prototype.</span>writeTreeToFile (tree, filename)](#apidoc.element.traceur.NodeCompiler.prototype.writeTreeToFile)
- description and source-code
```javascript
writeTreeToFile = function (tree, filename) {
  filename = this.normalize(filename);
  var compiledCode = this.write(tree, filename);
  if (this.options_.sourceMaps === 'file') {
    var sourcemap = this.getSourceMap();
    if (sourcemap) {
      var mapName = this.sourceMappingURL(filename);
      // Write the map file next to the output file.
      mapName = path.resolve(path.dirname(filename), mapName);
      writeFile(mapName, sourcemap);
    }
  }

  writeFile(filename, compiledCode);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
