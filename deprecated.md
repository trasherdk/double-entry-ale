

```sh
$ npm i
npm WARN deprecated ini@1.3.5: Please update to ini >=1.3.6 to avoid a prototype pollution issue
npm WARN deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
npm WARN deprecated minimatch@2.0.10: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm WARN deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
npm WARN deprecated graceful-fs@1.2.3: please upgrade to graceful-fs 4 for compatibility with current and future versions of Node.js
npm WARN deprecated json3@3.3.2: Please use the native JSON object instead of JSON 3
npm WARN deprecated natives@1.1.1: This module relies on Node.js's internals and will break at some point. Do not use it, and update to graceful-fs@4.x.
npm WARN deprecated mixin-deep@1.3.1: Critical bug fixed in v2.0.1, please upgrade to the latest version.
npm WARN deprecated set-value@2.0.0: Critical bug fixed in v3.0.1, please upgrade to the latest version.
npm WARN deprecated source-map-url@0.4.0: See https://github.com/lydell/source-map-url#deprecated
npm WARN deprecated graceful-fs@3.0.11: please upgrade to graceful-fs 4 for compatibility with current and future versions of Node.js
npm WARN deprecated gulp-util@3.0.8: gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5
npm WARN deprecated set-value@0.4.3: Critical bug fixed in v3.0.1, please upgrade to the latest version.
npm WARN deprecated minimatch@0.2.14: Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
npm WARN deprecated nomnom@1.5.2: Package no longer supported. Contact support@npmjs.com for more info.
npm WARN deprecated uuid@3.2.1: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
npm WARN deprecated source-map-resolve@0.5.1: See https://github.com/lydell/source-map-resolve#deprecated
npm WARN deprecated formidable@1.2.0: Please upgrade to latest, formidable@v2 or formidable@v3! Check these notes: https://bit.ly/2ZEqIau
npm WARN deprecated mkdirp@0.5.1: Legacy versions of mkdirp are no longer supported. Please update to mkdirp 1.x. (Note that the API surface has changed to use Promises in 1.x.)
npm WARN deprecated connect@2.30.2: connect 2.x series is deprecated
npm WARN deprecated axios@0.9.1: Critical security vulnerability fixed in v0.21.1. For more information, see https://github.com/axios/axios/pull/3410
npm WARN deprecated superagent@3.8.2: Please upgrade to v7.0.2+ of superagent.  We have fixed numerous issues with streams, form-data, attach(), filesystem errors not bubbling up (ENOENT on attach()), and all tests are now passing.  See the releases tab for more information at <https://github.com/visionmedia/superagent/releases>.
npm WARN deprecated terraformer-wkt-parser@1.1.2: terraformer-wkt-parser is deprecated and no longer supported. Please use @terraformer/wkt.
npm WARN deprecated sequelize@4.36.0: Please update to v6 or higher! A migration guide can be found here: https://sequelize.org/v6/manual/upgrade-to-v6.html
npm WARN deprecated terraformer@1.0.8: terraformer is deprecated and no longer supported. Please use @terraformer/arcgis.
npm WARN deprecated swagger-ui@2.2.10: No longer maintained, please upgrade to swagger-ui@3.
npm WARN deprecated swagger-editor@2.10.5: No longer maintained, please upgrade to swagger-editor@3.
npm WARN deprecated bower@1.8.2: This Bower version has SECURITY BUG THAT ALLOWS TO WRITE TO ARBITRARY FILE ON YOUR COMPUTER when you install malicious package. Please upgrade Bower to at least version 1.8.8 if you don't want to get hacked. More info: https://snyk.io/blog/severe-security-vulnerability-in-bowers-zip-archive-extraction/

added 637 packages, and audited 638 packages in 40s

70 vulnerabilities (4 low, 15 moderate, 38 high, 13 critical)
```

```sh
$ npm audit fix
npm WARN deprecated sequelize@4.44.4: Please update to v6 or higher! A migration guide can be found here: https://sequelize.org/v6/manual/upgrade-to-v6.html
npm WARN deprecated core-js@2.6.12: core-js@<3.4 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Please, upgrade your dependencies to the actual version of core-js.

added 3 packages, removed 18 packages, changed 31 packages, and audited 623 packages in 18s
```
