# JavaScript-2 Interview-2 Questions-(201-450) & Answers-(201-450)

---

### Table of Contents

| No. | Questions                                                                                                                                                     |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 201 | [How can you get the list of keys of any object](#how-can-you-get-the-list-of-keys-of-any-object)                                                             |
| 202 | [How do you create an object with prototype](#how-do-you-create-an-object-with-prototype)                                                                     |
| 203 | [What is a WeakSet](#what-is-a-weakset)                                                                                                                       |
| 204 | [What are the differences between a WeakSet and a Set](#what-are-the-differences-between-weakset-and-set)                                                     |
| 205 | [List down the collection of methods available on WeakSet](#list-down-the-collection-of-methods-available-on-weakset)                                         |
| 206 | [What is a WeakMap](#what-is-a-weakmap)                                                                                                                       |
| 207 | [What are the differences between a WeakMap and a Map](#what-are-the-differences-between-weakmap-and-map)                                                     |
| 208 | [List down the collection of methods available on WeakMap](#list-down-the-collection-of-methods-available-on-weakmap)                                         |
| 209 | [What is the purpose of uneval](#what-is-the-purpose-of-uneval)                                                                                               |
| 210 | [How do you encode an URL](#how-do-you-encode-an-url)                                                                                                         |
| 211 | [How do you decode an URL](#how-do-you-decode-an-url)                                                                                                         |
| 212 | [How do you print the contents of web page](#how-do-you-print-the-contents-of-web-page)                                                                       |
| 213 | [What is the difference between uneval and eval](#what-is-the-difference-between-uneval-and-eval)                                                             |
| 214 | [What is an anonymous function](#what-is-an-anonymous-function)                                                                                               |
| 215 | [What is the precedence order between local and global variables](#what-is-the-precedence-order-between-local-and-global-variables)                           |
| 216 | [What are javascript accessors](#what-are-javascript-accessors)                                                                                               |
| 217 | [How do you define property on Object constructor](#how-do-you-define-property-on-object-constructor)                                                         |
| 218 | [What is the difference between get and defineProperty](#what-is-the-difference-between-get-and-defineproperty)                                               |
| 219 | [What are the advantages of Getters and Setters](#what-are-the-advantages-of-getters-and-setters)                                                             |
| 220 | [Can I add getters and setters using defineProperty method](#can-i-add-getters-and-setters-using-defineproperty-method)                                       |
| 221 | [What is the purpose of switch-case](#what-is-the-purpose-of-switch-case)                                                                                     |
| 222 | [What are the conventions to be followed for the usage of switch case](#what-are-the-conventions-to-be-followed-for-the-usage-of-switch-case)                 |
| 223 | [What are primitive data types](#what-are-primitive-data-types)                                                                                               |
| 224 | [What are the different ways to access object properties](#what-are-the-different-ways-to-access-object-properties)                                           |
| 225 | [What are the function parameter rules](#what-are-the-function-parameter-rules)                                                                               |
| 226 | [What is an error object](#what-is-an-error-object)                                                                                                           |
| 227 | [When you get a syntax error](#when-you-get-a-syntax-error)                                                                                                   |
| 228 | [What are the different error names from error object](#what-are-the-different-error-names-from-error-object)                                                 |
| 229 | [What are the various statements in error handling](#what-are-the-various-statements-in-error-handling)                                                       |
| 230 | [What are the two types of loops in javascript](#what-are-the-two-types-of-loops-in-javascript)                                                               |
| 231 | [What is nodejs](#what-is-nodejs)                                                                                                                             |
| 232 | [What is an Intl object](#what-is-an-intl-object)                                                                                                             |
| 233 | [How do you perform language specific date and time formatting](#how-do-you-perform-language-specific-date-and-time-formatting)                               |
| 234 | [What is an Iterator](#what-is-an-iterator)                                                                                                                   |
| 235 | [How does the synchronous iteration work](#how-does-synchronous-iteration-works)                                                                              |
| 236 | [What is an event loop](#what-is-an-event-loop)                                                                                                               |
| 237 | [What is call stack](#what-is-call-stack)                                                                                                                     |
| 238 | [What is an event queue](#what-is-an-event-queue)                                                                                                             |
| 239 | [What is a decorator](#what-is-a-decorator)                                                                                                                   |
| 240 | [What are the properties of Intl object](#what-are-the-properties-of-intl-object)                                                                             |
| 241 | [What is an Unary operator](#what-is-an-unary-operator)                                                                                                       |
| 242 | [How do you sort elements in an array](#how-do-you-sort-elements-in-an-array)                                                                                 |
| 243 | [What is the purpose of compareFunction while sorting arrays](#what-is-the-purpose-of-comparefunction-while-sorting-arrays)                                   |
| 244 | [How do you reversing an array](#how-do-you-reversing-an-array)                                                                                               |
| 245 | [How do you find min and max value in an array](#how-do-you-find-min-and-max-value-in-an-array)                                                               |
| 246 | [How do you find min and max values without Math functions](#how-do-you-find-min-and-max-values-without-math-functions)                                       |
| 247 | [What is an empty statement and purpose of it](#what-is-an-empty-statement-and-purpose-of-it)                                                                 |
| 248 | [How do you get metadata of a module](#how-do-you-get-metadata-of-a-module)                                                                                   |
| 249 | [What is a comma operator](#what-is-a-comma-operator)                                                                                                         |
| 250 | [What is the advantage of a comma operator](#what-is-the-advantage-of-a-comma-operator)                                                                       |
| 251 | [What is typescript](#what-is-typescript)                                                                                                                     |
| 252 | [What are the differences between javascript and typescript](#what-are-the-differences-between-javascript-and-typescript)                                     |
| 253 | [What are the advantages of typescript over javascript](#what-are-the-advantages-of-typescript-over-javascript)                                               |
| 254 | [What is an object initializer](#what-is-an-object-initializer)                                                                                               |
| 255 | [What is a constructor method](#what-is-a-constructor-method)                                                                                                 |
| 256 | [What happens if you write constructor more than once in a class](#what-happens-if-you-write-constructor-more-than-once-in-a-class)                           |
| 257 | [How do you call the constructor of a parent class](#how-do-you-call-the-constructor-of-a-parent-class)                                                       |
| 258 | [How do you get the prototype of an object](#how-do-you-get-the-prototype-of-an-object)                                                                       |
| 259 | [What happens If I pass string type for getPrototype method](#what-happens-if-i-pass-string-type-for-getprototype-method)                                     |
| 260 | [How do you set prototype of one object to another](#how-do-you-set-prototype-of-one-object-to-another)                                                       |
| 261 | [How do you check whether an object can be extendable or not](#how-do-you-check-whether-an-object-can-be-extendable-or-not)                                   |
| 262 | [How do you prevent an object to extend](#how-do-you-prevent-an-object-to-extend)                                                                             |
| 263 | [What are the different ways to make an object non-extensible](#what-are-the-different-ways-to-make-an-object-non-extensible)                                 |
| 264 | [How do you define multiple properties on an object](#how-do-you-define-multiple-properties-on-an-object)                                                     |
| 265 | [What is MEAN in javascript](#what-is-mean-in-javascript)                                                                                                     |
| 266 | [What Is Obfuscation in javascript](#what-is-obfuscation-in-javascript)                                                                                       |
| 267 | [Why do you need Obfuscation](#why-do-you-need-obfuscation)                                                                                                   |
| 268 | [What is Minification](#what-is-minification)                                                                                                                 |
| 269 | [What are the advantages of minification](#what-are-the-advantages-of-minification)                                                                           |
| 270 | [What are the differences between Obfuscation and Encryption](#what-are-the-differences-between-obfuscation-and-encryption)                                   |
| 271 | [What are the common tools used for minification](#what-are-the-common-tools-used-for-minification)                                                           |
| 272 | [How do you perform form validation using javascript](#how-do-you-perform-form-validation-using-javascript)                                                   |
| 273 | [How do you perform form validation without javascript](#how-do-you-perform-form-validation-without-javascript)                                               |
| 274 | [What are the DOM methods available for constraint validation](#what-are-the-dom-methods-available-for-constraint-validation)                                 |
| 275 | [What are the available constraint validation DOM properties](#what-are-the-available-constraint-validation-dom-properties)                                   |
| 276 | [What are the list of validity properties](#what-are-the-list-of-validity-properties)                                                                         |
| 277 | [Give an example usage of rangeOverflow property](#give-an-example-usage-of-rangeoverflow-property)                                                           |
| 278 | [Is enums feature available in javascript](#is-enums-feature-available-in-javascript)                                                                         |
| 279 | [What is an enum](#What-is-an-enum)                                                                                                                           |
| 280 | [How do you list all properties of an object](#how-do-you-list-all-properties-of-an-object)                                                                   |
| 281 | [How do you get property descriptors of an object](#how-do-you-get-property-descriptors-of-an-object)                                                         |
| 282 | [What are the attributes provided by a property descriptor](#what-are-the-attributes-provided-by-a-property-descriptor)                                       |
| 283 | [How do you extend classes](#how-do-you-extend-classes)                                                                                                       |
| 284 | [How do I modify the url without reloading the page](#how-do-i-modify-the-url-without-reloading-the-page)                                                     |
| 285 | [How do you check whether an array includes a particular value or not](#how-do-you-check-whether-an-array-includes-a-particular-value-or-not)                 |
| 286 | [How do you compare scalar arrays](#how-do-you-compare-scalar-arrays)                                                                                         |
| 287 | [How to get the value from get parameters](#how-to-get-the-value-from-get-parameters)                                                                         |
| 288 | [How do you print numbers with commas as thousand separators](#how-do-you-print-numbers-with-commas-as-thousand-separators)                                   |
| 289 | [What is the difference between java and javascript](#what-is-the-difference-between-java-and-javascript)                                                     |
| 290 | [Does javascript supports namespace](#does-javascript-supports-namespace)                                                                                     |
| 291 | [How do you declare namespace](#how-do-you-declare-namespace)                                                                                                 |
| 292 | [How do you invoke javascript code in an iframe from parent page](#how-do-you-invoke-javascript-code-in-an-iframe-from-parent-page)                           |
| 293 | [How do get the timezone offset from date](#how-do-get-the-timezone-offset-from-date)                                                                         |
| 294 | [How do you load CSS and JS files dynamically](#how-do-you-load-css-and-js-files-dynamically)                                                                 |
| 295 | [What are the different methods to find HTML elements in DOM](#what-are-the-different-methods-to-find-html-elements-in-dom)                                   |
| 296 | [What is jQuery](#what-is-jquery)                                                                                                                             |
| 297 | [What is V8 JavaScript engine](#what-is-v8-javascript-engine)                                                                                                 |
| 298 | [Why do we call javascript as dynamic language](#why-do-we-call-javascript-as-dynamic-language)                                                               |
| 299 | [What is a void operator](#what-is-a-void-operator)                                                                                                           |
| 300 | [How to set the cursor to wait](#how-to-set-the-cursor-to-wait)                                                                                               |
| 301 | [How do you create an infinite loop](#how-do-you-create-an-infinite-loop)                                                                                     |
| 302 | [Why do you need to avoid with statement](#why-do-you-need-to-avoid-with-statement)                                                                           |
| 303 | [What is the output of below for loops](#what-is-the-output-of-below-for-loops)                                                                               |
| 304 | [List down some of the features of ES6](#list-down-some-of-the-features-of-es6)                                                                               |
| 305 | [What is ES6](#what-is-es6)                                                                                                                                   |
| 306 | [Can I redeclare let and const variables](#can-I-redeclare-let-and-const-variables)                                                                           |
| 307 | [Is const variable makes the value immutable](#is-const-variable-makes-the-value-immutable)                                                                   |
| 308 | [What are default parameters](#what-are-default-parameters)                                                                                                   |
| 309 | [What are template literals](#what-are-template-literals)                                                                                                     |
| 310 | [How do you write multi-line strings in template literals](#how-do-you-write-multi-line-strings-in-template-literals)                                         |
| 311 | [What are nesting templates](#what-are-nesting-templates)                                                                                                     |
| 312 | [What are tagged templates](#what-are-tagged-templates)                                                                                                       |
| 313 | [What are raw strings](#what-are-raw-strings)                                                                                                                 |
| 314 | [What is destructuring assignment](#what-is-destructuring-assignment)                                                                                         |
| 315 | [What are default values in destructuring assignment](#what-are-default-values-in-destructuring-assignment)                                                   |
| 316 | [How do you swap variables in destructuring assignment](#how-do-you-swap-variables-in-destructuring-assignment)                                               |
| 317 | [What are enhanced object literals](#what-are-enhanced-object-literals)                                                                                       |
| 318 | [What are dynamic imports](#what-are-dynamic-imports)                                                                                                         |
| 319 | [What are the use cases for dynamic imports](#what-are-the-use-cases-for-dynamic-imports)                                                                     |
| 320 | [What are typed arrays](#what-are-typed-arrays)                                                                                                               |
| 321 | [What are the advantages of module loaders](#what-are-the-advantages-of-module-loaders)                                                                       |
| 322 | [What is collation](#what-is-collation)                                                                                                                       |
| 323 | [What is for...of statement](#what-is-forof-statement)                                                                                                        |
| 324 | [What is the output of below spread operator array](#what-is-the-output-of-below-spread-operator-array)                                                       |
| 325 | [Is PostMessage secure](#is-postmessage-secure)                                                                                                               |
| 326 | [What are the problems with postmessage target origin as wildcard](#what-are-the-problems-with-postmessage-target-origin-as-wildcard)                         |
| 327 | [How do you avoid receiving postMessages from attackers](#how-do-you-avoid-receiving-postmessages-from-attackers)                                             |
| 328 | [Can I avoid using postMessages completely](#can-i-avoid-using-postmessages-completely)                                                                       |
| 329 | [Is postMessages synchronous](#is-postmessages-synchronous)                                                                                                   |
| 330 | [What paradigm is Javascript](#what-paradigm-is-javascript)                                                                                                   |
| 331 | [What is the difference between internal and external javascript](#what-is-the-difference-between-internal-and-external-javascript)                           |
| 332 | [Is JavaScript faster than server side script](#is-javascript-faster-than-server-side-script)                                                                 |
| 333 | [How do you get the status of a checkbox](#how-do-you-get-the-status-of-a-checkbox)                                                                           |
| 334 | [What is the purpose of double tilde operator](#what-is-the-purpose-of-double-tilde-operator)                                                                 |
| 335 | [How do you convert character to ASCII code](#how-do-you-convert-character-to-ascii-code)                                                                     |
| 336 | [What is ArrayBuffer](#what-is-arraybuffer)                                                                                                                   |
| 337 | [What is the output of below string expression](#what-is-the-output-of-below-string-expression)                                                               |
| 338 | [What is the purpose of Error object](#what-is-the-purpose-of-error-object)                                                                                   |
| 339 | [What is the purpose of EvalError object](#what-is-the-purpose-of-evalerror-object)                                                                           |
| 340 | [What are the list of cases error thrown from non-strict mode to strict mode](#what-are-the-list-of-cases-error-thrown-from-non-strict-mode-to-strict-mode)   |
| 341 | [Do all objects have prototypes](#do-all-objects-have-prototypes)                                                                                             |
| 342 | [What is the difference between a parameter and an argument](#what-is-the-difference-between-a-parameter-and-an-argument)                                     |
| 343 | [What is the purpose of some method in arrays](#what-is-the-purpose-of-some-method-in-arrays)                                                                 |
| 344 | [How do you combine two or more arrays](#how-do-you-combine-two-or-more-arrays)                                                                               |
| 345 | [What is the difference between Shallow and Deep copy](#what-is-the-difference-between-shallow-and-deep-copy)                                                 |
| 346 | [How do you create specific number of copies of a string](#how-do-you-create-specific-number-of-copies-of-a-string)                                           |
| 347 | [How do you return all matching strings against a regular expression](#how-do-you-return-all-matching-strings-against-a-regular-expression)                   |
| 348 | [How do you trim a string at the beginning or ending](#how-do-you-trim-a-string-at-the-beginning-or-ending)                                                   |
| 349 | [What is the output of below console statement with unary operator](#what-is-the-output-of-below-console-statement-with-unary-operator)                       |
| 350 | [Does javascript uses mixins](#does-javascript-uses-mixins)                                                                                                   |
| 351 | [What is a thunk function](#what-is-a-thunk-function)                                                                                                         |
| 352 | [What are asynchronous thunks](#what-are-asynchronous-thunks)                                                                                                 |
| 353 | [What is the output of below function calls](#what-is-the-output-of-below-function-calls)                                                                     |
| 354 | [How to remove all line breaks from a string](#how-to-remove-all-line-breaks-from-a-string)                                                                   |
| 355 | [What is the difference between reflow and repaint](#what-is-the-difference-between-reflow-and-repaint)                                                       |
| 356 | [What happens with negating an array](#what-happens-with-negating-an-array)                                                                                   |
| 357 | [What happens if we add two arrays](#what-happens-if-we-add-two-arrays)                                                                                       |
| 358 | [What is the output of prepend additive operator on falsy values](#what-is-the-output-of-prepend-additive-operator-on-falsy-values)                           |
| 359 | [How do you create self string using special characters](#how-do-you-create-self-string-using-special-characters)                                             |
| 360 | [How do you remove falsy values from an array](#how-do-you-remove-falsy-values-from-an-array)                                                                 |
| 361 | [How do you get unique values of an array](#how-do-you-get-unique-values-of-an-array)                                                                         |
| 362 | [What is destructuring aliases](#what-is-destructuring-aliases)                                                                                               |
| 363 | [How do you map the array values without using map method](#how-do-you-map-the-array-values-without-using-map-method)                                         |
| 364 | [How do you empty an array](#how-do-you-empty-an-array)                                                                                                       |
| 365 | [How do you round numbers to certain decimals](#how-do-you-rounding-numbers-to-certain-decimals)                                                              |
| 366 | [What is the easiest way to convert an array to an object](#what-is-the-easiest-way-to-convert-an-array-to-an-object)                                         |
| 367 | [How do you create an array with some data](#how-do-you-create-an-array-with-some-data)                                                                       |
| 368 | [What are the placeholders from console object](#what-are-the-placeholders-from-console-object)                                                               |
| 369 | [Is it possible to add CSS to console messages](#is-it-possible-to-add-css-to-console-messages)                                                               |
| 370 | [What is the purpose of dir method of console object](#what-is-the-purpose-of-dir-method-of-console-object)                                                   |
| 371 | [Is it possible to debug HTML elements in console](#is-it-possible-to-debug-html-elements-in-console)                                                         |
| 372 | [How do you display data in a tabular format using console object](#how-do-you-display-data-in-a-tabular-format-using-console-object)                         |
| 373 | [How do you verify that an argument is a Number or not](#how-do-you-verify-that-an-argument-is-a-number-or-not)                                               |
| 374 | [How do you create copy to clipboard button](#how-do-you-create-copy-to-clipboard-button)                                                                     |
| 375 | [What is the shortcut to get timestamp](#what-is-the-shortcut-to-get-timestamp)                                                                               |
| 376 | [How do you flattening multi dimensional arrays](#how-do-you-flattening-multi-dimensional-arrays)                                                             |
| 377 | [What is the easiest multi condition checking](#what-is-the-easiest-multi-condition-checking)                                                                 |
| 378 | [How do you capture browser back button](#how-do-you-capture-browser-back-button)                                                                             |
| 379 | [How do you disable right click in the web page](#how-do-you-disable-right-click-in-the-web-page)                                                             |
| 380 | [What are wrapper objects](#what-are-wrapper-objects)                                                                                                         |
| 381 | [What is AJAX](#what-is-ajax)                                                                                                                                 |
| 382 | [What are the different ways to deal with Asynchronous Code](#what-are-the-different-ways-to-deal-with-asynchronous-code)                                     |
| 383 | [How to cancel a fetch request](#how-to-cancel-a-fetch-request)                                                                                               |
| 384 | [What is web speech API](#what-is-web-speech-api)                                                                                                             |
| 385 | [What is minimum timeout throttling](#what-is-minimum-timeout-throttling)                                                                                     |
| 386 | [How do you implement zero timeout in modern browsers](#how-do-you-implement-zero-timeout-in-modern-browsers)                                                 |
| 387 | [What are tasks in event loop](#what-are-tasks-in-event-loop)                                                                                                 |
| 388 | [What is microtask](#what-is-microtask)                                                                                                                       |
| 389 | [What are different event loops](#what-are-different-event-loops)                                                                                             |
| 390 | [What is the purpose of queueMicrotask](#what-is-the-purpose-of-queuemicrotask)                                                                               |
| 391 | [How do you use javascript libraries in typescript file](#how-do-you-use-javascript-libraries-in-typescript-file)                                             |
| 392 | [What are the differences between promises and observables](#what-are-the-differences-between-promises-and-observables)                                       |
| 393 | [What is heap](#what-is-heap)                                                                                                                                 |
| 394 | [What is an event table](#what-is-an-event-table)                                                                                                             |
| 395 | [What is a microTask queue](#what-is-a-microtask-queue)                                                                                                       |
| 396 | [What is the difference between shim and polyfill](#what-is-the-difference-between-shim-and-polyfill)                                                         |
| 397 | [How do you detect primitive or non primitive value type](#how-do-you-detect-primitive-or-non-primitive-value-type)                                           |
| 398 | [What is babel](#what-is-babel)                                                                                                                               |
| 399 | [Is Node.js completely single threaded](#is-nodejs-completely-single-threaded)                                                                                |
| 400 | [What are the common use cases of observables](#what-are-the-common-use-cases-of-observables)                                                                 |
| 401 | [What is RxJS](#what-is-rxjs)                                                                                                                                 |
| 402 | [What is the difference between Function constructor and function declaration](#what-is-the-difference-between-function-constructor-and-function-declaration) |
| 403 | [What is a Short circuit condition](#what-is-a-short-circuit-condition)                                                                                       |
| 404 | [What is the easiest way to resize an array](#what-is-the-easiest-way-to-resize-an-array)                                                                     |
| 405 | [What is an observable](#what-is-an-observable)                                                                                                               |
| 406 | [What is the difference between function and class declarations](#what-is-the-difference-between-function-and-class-declarations)                             |
| 407 | [What is an async function](#what-is-an-async-function)                                                                                                       |
| 408 | [How do you prevent promises swallowing errors](#how-do-you-prevent-promises-swallowing-errors)                                                               |
| 409 | [What is deno](#what-is-deno)                                                                                                                                 |
| 410 | [How do you make an object iterable in javascript](#how-do-you-make-an-object-iterable-in-javascript)                                                         |
| 411 | [What is a Proper Tail Call](#what-is-a-proper-tail-call)                                                                                                     |
| 412 | [How do you check an object is a promise or not](#how-do-you-check-an-object-is-a-promise-or-not)                                                             |
| 413 | [How to detect if a function is called as constructor](#how-to-detect-if-a-function-is-called-as-constructor)                                                 |
| 414 | [What are the differences between arguments object and rest parameter](#what-are-the-differences-between-arguments-object-and-rest-parameter)                 |
| 415 | [What are the differences between spread operator and rest parameter](#what-are-the-differences-between-spread-operator-and-rest-parameter)                   |
| 416 | [What are the different kinds of generators](#what-are-the-different-kinds-of-generators)                                                                     |
| 417 | [What are the built-in iterables](#what-are-the-built-in-iterables)                                                                                           |
| 418 | [What are the differences between for...of and for...in statements](#what-are-the-differences-between-forof-and-forin-statements)                             |
| 419 | [How do you define instance and non-instance properties](#how-do-you-define-instance-and-non-instance-properties)                                             |
| 420 | [What is the difference between isNaN and Number.isNaN?](#what-is-the-difference-between-isnan-and-numberisnan)                                               |
| 421 | [How to invoke an IIFE without any extra brackets?](#how-to-invoke-an-iife-without-any-extra-brackets)                                                        |
| 422 | [Is that possible to use expressions in switch cases?](#is-that-possible-to-use-expressions-in-switch-cases)                                                  |
| 423 | [What is the easiest way to ignore promise errors?](#what-is-the-easiest-way-to-ignore-promise-errors)                                                        |
| 424 | [How do style the console output using CSS?](#how-do-style-the-console-output-using-css)                                                                      |
| 425 | [What is nullish coalescing operator (??)?](#what-is-nullish-coalescing-operator)                                                                             |
| 426 | [How do you group and nest console output?](#how-do-you-group-and-nest-console-output)                                                                        |
| 427 | [What is the difference between dense and sparse arrays?](#what-is-the-difference-between-dense-and-sparse-arrays)                                            |
| 428 | [What are the different ways to create sparse arrays?](#what-are-the-different-ways-to-create-sparse-arrays)                                                  |
| 429 | [What is the difference between setTimeout, setImmediate and process.nextTick?](#what-is-the-difference-between-settimeout-setimmediate-and-processnexttick)  |
| 430 | [How do you reverse an array without modifying original array?](#how-do-you-reverse-an-array-without-modifying-original-array)                                |
| 431 | [How do you create custom HTML element?](#how-do-you-create-custom-html-element)                                                                              |
| 432 | [What is global execution context?](#what-is-global-execution-context)                                                                                        |
| 433 | [What is function execution context?](#what-is-function-execution-context)                                                                                    |
| 434 | [What is debouncing?](#what-is-debouncing)                                                                                                                    |
| 435 | [What is throttling?](#what-is-throttling)                                                                                                                    |
| 436 | [What is optional chaining?](#what-is-optional-chaining)                                                                                                      |
| 437 | [What is an environment record?](#what-is-an-environment-record)                                                                                              |
| 438 | [How to verify if a variable is an array?](#how-to-verify-if-a-variable-is-an-array)                                                                          |
| 439 | [What is pass by value and pass by reference?](#what-is-pass-by-value-and-pass-by-reference)                                                                  |
| 440 | [What are the differences between primitives and non-primitives?](#what-are-the-differences-between-primitives-and-non-primitives)                            |
| 441 | [What are hidden classes?](#what-are-hidden-classes)                                                                                                          |
| 442 | [What is inline caching?](#what-is-inline-caching)                                                                                                            |
| 443 | [How do you create your own bind method using either call or apply method?](#how-do-you-create-your-own-bind-method-using-either-call-or-apply-method)        |
| 444 | [What are the differences between pure and impure functions?](#what-are-the-differences-between-pure-and-impure-functions?)                                   |
| 445 | [What is referential transparency?](#what-is-referential-transparency)                                                                                        |
| 446 | [What are the possible side-effects in javascript?](#what-are-the-possible-side-effects-in-javascript)                                                        |
| 447 | [What are compose and pipe functions?](#what-are-compose-and-pipe-functions)                                                                                  |
| 448 | [What is module pattern?](#what-is-module-pattern)                                                                                                            |
| 449 | [What is Function Composition?](#what-is-function-composition)                                                                                                |
| 450 | [How to use await outside of async function prior to ES2022?](#how-to-use-await-outside-of-async-function-prior-to-es2022)                                    |


201.  ### How can you get the list of keys of any object

      You can use the `Object.keys()` method which is used to return an array of a given object's own property names, in the same order as we get with a normal loop. For example, you can get the keys of a user object,

      ```javascript
      const user = {
        name: "John",
        gender: "male",
        age: 40,
      };

      console.log(Object.keys(user)); //['name', 'gender', 'age']
      ```

      **[⬆ Back to Top](#table-of-contents)**

### কোনও অবজেক্টের কী গুলি পেতে কিভাবে করবেন

আপনি `Object.keys()` মেথড ব্যবহার করতে পারেন, যা একটি নির্দিষ্ট অবজেক্টের নিজস্ব মালিক নেমগুলির একটি অ্যারে ফেরত দেয়, একই অর্ডারে যেভাবে সাধারিত লুপে পাওয়া যায়। উদাহরণস্বরূপ, আপনি একটি ব্যবহারকারী অবজেক্টের কীগুলি পেতে পারেন,

```javascript
const user = {
  name: "John",
  gender: "male",
  age: 40,
};

console.log(Object.keys(user)); //['name', 'gender', 'age']
```

202.  ### How do you create an object with prototype

      The Object.create() method is used to create a new object with the specified prototype object and properties. i.e, It uses an existing object as the prototype of the newly created object. It returns a new object with the specified prototype object and properties.

      ```javascript
      const user = {
        name: "John",
        printInfo: function () {
          console.log(`My name is ${this.name}.`);
        },
      };

      const admin = Object.create(user);

      admin.name = "Nick"; // Remember that "name" is a property set on "admin" but not on "user" object

      admin.printInfo(); // My name is Nick
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কীভাবে আপনি একটি অবজেক্ট প্রোটোটাইপ সহ তৈরি করবেন

`Object.create()` মেথডটি ব্যবহার করা হয় একটি নির্দিষ্ট প্রোটোটাইপ অবজেক্ট এবং বৈশিষ্ট্যসহ একটি নতুন অবজেক্ট তৈরি করতে। অর্থাৎ, এটি একটি নতুন অবজেক্ট তৈরি করতে একটি বিদ্যমান অবজেক্ট ব্যবহার করে। এটি নির্দিষ্ট প্রোটোটাইপ অবজেক্ট এবং বৈশিষ্ট্যসহ একটি নতুন অবজেক্ট ফিরিয়ে দেয়।

```javascript
const user = {
  name: "John",
  printInfo: function () {
    console.log(`My name is ${this.name}.`);
  },
};

const admin = Object.create(user);

admin.name = "Nick"; // মনে রাখবেন, "name" একটি প্রপার্টি যা "admin" তে সেট করা হয়েছে কিন্তু "user" অবজেক্টে নয়

admin.printInfo(); // My name is Nick
```
203.  ### What is a WeakSet

      WeakSet is used to store a collection of weakly(weak references) held objects. The syntax would be as follows,

      ```javascript
      new WeakSet([iterable]);
      ```

      Let's see the below example to explain it's behavior,

      ```javascript
      var ws = new WeakSet();
      var user = {};
      ws.add(user);
      ws.has(user); // true
      ws.delete(user); // removes user from the set
      ws.has(user); // false, user has been removed
      ```

      **[⬆ Back to Top](#table-of-contents)**
### ওয়ীকসেট (WeakSet)

`WeakSet` হলো এমন একটি অবজেক্ট যা স্বয়ংক্রিয়ভাবে অবজেক্ট রেফারেন্স ধরে রাখে, যার জন্য অবজেক্ট গুলির ওই সেটে থাকায় তারা গতি দেয় না (weakly held objects)। এর সিনট্যাক্স হলো,

```javascript
new WeakSet([iterable]);
```
204.  ### What are the differences between WeakSet and Set

      The main difference is that references to objects in Set are strong while references to objects in WeakSet are weak. i.e, An object in WeakSet can be garbage collected if there is no other reference to it.
      Other differences are,

      1.  Sets can store any value Whereas WeakSets can store only collections of objects
      2.  WeakSet does not have size property unlike Set
      3.  WeakSet does not have methods such as clear, keys, values, entries, forEach.
      4.  WeakSet is not iterable.

      **[⬆ Back to Top](#table-of-contents)**

### ওয়ীকসেট এবং সেটের মধ্যে পার্থক্য

প্রধান পার্থক্য হলো যে সেটে অবজেক্টের রেফারেন্সগুলি স্ট্রং থাকে, সাথে তারা গারবেজ কালেকশনে যাত্রা করতে পারে না, সেইসাথে ওয়ীকসেটে অবজেক্টের রেফারেন্সগুলি ওই সেটে যখন থাকবে তখন তাদের জন্য ওই রেফারেন্সগুলি ওয়ীক হবে। এটি মূলত,

1. সেট যেকোন মান সংরক্ষণ করতে পারে কিন্তু ওয়ীকসেট কেবল অবজেক্ট সমছুহরু সংরক্ষণ করতে পারে
2. ওয়ীকসেটের কোনও সাইজ প্রপার্টি থাকে না, তার বিপরীতে সেটের একটি সাইজ প্রপার্টি থাকে
3. ওয়ীকসেটে ক্লিয়ার, কী, ভ্যালু, এন্ট্রিজ, ফরইচ, ইত্যাদির মধ্যে কোনও মেথড নেই
4. ওয়ীকসেট ইটারেট করা সম্ভব নয়।

**[⬆ উপরে ফিরুন](#table-of-contents)**


205.  ### List down the collection of methods available on WeakSet

      Below are the list of methods available on WeakSet,

      1.  add(value): A new object is appended with the given value to the weakset
      2.  delete(value): Deletes the value from the WeakSet collection.
      3.  has(value): It returns true if the value is present in the WeakSet Collection, otherwise it returns false.

      Let's see the functionality of all the above methods in an example,

      ```javascript
      var weakSetObject = new WeakSet();
      var firstObject = {};
      var secondObject = {};
      // add(value)
      weakSetObject.add(firstObject);
      weakSetObject.add(secondObject);
      console.log(weakSetObject.has(firstObject)); //true
      weakSetObject.delete(secondObject);
      ```

      **[⬆ Back to Top](#table-of-contents)**
### WeakSet মেথড সমূহের সংগ্রহ

নীচে ওয়ীকসেটে প্রযোজ্য মেথডগুলির তালিকা রয়েছে,

1.  **add(value):** একটি নতুন অবজেক্ট দেওয়া হয় যেটি উইকসেটে সঙ্গীত হয়।
2.  **delete(value):** উইকসেট সংগ্রহ থেকে মান মুছে ফেলে।
3.  **has(value):** এটি মান যদি উইকসেট সংগ্রহে উপস্থিত হয় তবে সত্য ফিরিয়ে দেয়, অন্যথায় এটি মিথ্যা ফিরিয়ে দেয়।

উপরের সমস্ত মেথডের কাজকর্ম একটি উদাহরণে দেখা যাক,

```javascript
var weakSetObject = new WeakSet();
var firstObject = {};
var secondObject = {};
// add(value)
weakSetObject.add(firstObject);
weakSetObject.add(secondObject);
console.log(weakSetObject.has(firstObject)); //true
weakSetObject.delete(secondObject);
```
206.  ### What is a WeakMap

      The WeakMap object is a collection of key/value pairs in which the keys are weakly referenced. In this case, keys must be objects and the values can be arbitrary values. The syntax is looking like as below,

      ```javascript
      new WeakMap([iterable]);
      ```

      Let's see the below example to explain it's behavior,

      ```javascript
      var ws = new WeakMap();
      var user = {};
      ws.set(user);
      ws.has(user); // true
      ws.delete(user); // removes user from the map
      ws.has(user); // false, user has been removed
      ```

      **[⬆ Back to Top](#table-of-contents)**

### WeakMap

ওয়ীকম্যাপ অবজেক্টটি একটি কী/মান জোড়ের সংগ্রহ, যেখানে কীগুলি শক্তিহীনভাবে রেফারেন্স করা হয়। এই ক্ষেত্রে, কী অবজেক্ট হতে হবে এবং মান বিচ্ছিন্ন মান হতে পারে। নোট: ওয়ীকম্যাপগুলি সাপেক্ষে আবজেক্টগুলির জন্য শোক্তিহীন রেফারেন্স ব্যবহৃত হয়। সিনট্যাক্স নিম্নের মত,

```javascript
new WeakMap([iterable]);
নিচে এর আচরণ বোঝানোর জন্য একটি উদাহরণ দেখা হয়েছে,
var ws = new WeakMap();
var user = {};
ws.set(user);
ws.has(user); // true
ws.delete(user); // removes user from the map
ws.has(user); // false, user has been removed
```

207.  ### What are the differences between WeakMap and Map

      The main difference is that references to key objects in Map are strong while references to key objects in WeakMap are weak. i.e, A key object in WeakMap can be garbage collected if there is no other reference to it.
      Other differences are,

      1.  Maps can store any key type Whereas WeakMaps can store only collections of key objects
      2.  WeakMap does not have size property unlike Map
      3.  WeakMap does not have methods such as clear, keys, values, entries, forEach.
      4.  WeakMap is not iterable.

      **[⬆ Back to Top](#table-of-contents)**

### WeakMap vs Map

মেইন পার্থক্য হলো, ম্যাপে কী অবজেক্টগুলির রেফারেন্স স্ট্রং হয়, যখন ওয়ীকম্যাপে কী অবজেক্টগুলির রেফারেন্স ওয়ীক হয়। এটার মাধ্যমে, ওয়ীকম্যাপে কোনও কী অবজেক্ট গার্বেজ কালেক্ট হতে পারে যদি এর অন্য কোনও রেফারেন্স না থাকে।
অন্যান্য পার্থক্যগুলি হলো,

1. ম্যাপ যে কোনও কী প্রকার সংরক্ষণ করতে পারে তবে ওয়ীকম্যাপ কেবল কী অবজেক্টগুলির সংরক্ষণ করতে পারে
2. ওয়ীকম্যাপে সাইজ প্রপার্টি ছাড়া, ম্যাপে সাইজ প্রপার্টি থাকে
3. ওয়ীকম্যাপে clear, keys, values, entries, forEach এর মতো মেথড নেই।
4. ওয়ীকম্যাপ একটি ইটারেটর হিসেবে কাজ করে না।

**[⬆ উপরে ফিরুন](#table-of-contents)**

208.  ### List down the collection of methods available on WeakMap

      Below are the list of methods available on WeakMap,

      1.  set(key, value): Sets the value for the key in the WeakMap object. Returns the WeakMap object.
      2.  delete(key): Removes any value associated to the key.
      3.  has(key): Returns a Boolean asserting whether a value has been associated to the key in the WeakMap object or not.
      4.  get(key): Returns the value associated to the key, or undefined if there is none.
          Let's see the functionality of all the above methods in an example,

      ```javascript
      var weakMapObject = new WeakMap();
      var firstObject = {};
      var secondObject = {};
      // set(key, value)
      weakMapObject.set(firstObject, "John");
      weakMapObject.set(secondObject, 100);
      console.log(weakMapObject.has(firstObject)); //true
      console.log(weakMapObject.get(firstObject)); // John
      weakMapObject.delete(secondObject);
      ```

      **[⬆ Back to Top](#table-of-contents)**
### WeakMap Methods

নোট: ওয়ীকম্যাপের মেথডগুলি হলো,

1. `set(key, value)`: ওয়ীকম্যাপ অবজেক্টে কীর জন্য মান সেট করে। ওয়ীকম্যাপ অবজেক্ট রিটার্ন করে।
2. `delete(key)`: কোনও মৌল্য যোগদান করা হোক না কেন, মৌল্য মুছে ফেলে।
3. `has(key)`: ওয়ীকম্যাপ অবজেক্টে কোনও মৌল্যই কীর সাথে যুক্ত হয়েছে কিনা তা যাচাই করে একটি বুলিয়ান দেয়।
4. `get(key)`: কীর সাথে যোগদান করা মৌল্যটি ফিরিয়ে দেয়, বা কোনও না থাকলে undefined ফিরিয়ে দেয়।

**[⬆ উপরে ফিরুন](#table-of-contents)**


209.  ### What is the purpose of uneval

      The uneval() is an inbuilt function which is used to create a string representation of the source code of an Object. It is a top-level function and is not associated with any object. Let's see the below example to know more about it's functionality,

      ```javascript
      var a = 1;
      uneval(a); // returns a String containing 1
      uneval(function user() {}); // returns "(function user(){})"
      ```

      The `uneval()` function has been deprecated. It is recommended to use `toString()` for functions and `JSON.toStringify()` for other cases.

      ```javascript
      function user() {}
      console.log(user.toString()); // returns "(function user(){})"
      ```

      **[⬆ Back to Top](#table-of-contents)**

### `uneval` এর উদ্দেশ্য

`uneval()` হলো একটি অভ্যন্তরীণ ফাংশন যা একটি অবজেক্টের উৎস কোডের একটি স্ট্রিং প্রতিষ্ঠান করতে ব্যবহৃত হয়। তবে, গুরুত্বপূর্ণ বিষয় হলো `uneval()` ফাংশনটি ডিপ্রিকেট করা হয়েছে। বরং, এর পরিবর্তে অন্য বিকল্পগুলি ব্যবহার করা হয়:

1. ফাংশনগুলির জন্য `toString()` ব্যবহার করতে পারেন:

    ```javascript
    function user() {}
    console.log(user.toString()); // "(function user(){})"
    ```

2. অন্যান্য ক্ষেত্রে, `JSON.stringify()` ব্যবহার করতে পারেন:

    ```javascript
    var a = 1;
    JSON.stringify(a); // "1"
    ```

**[⬆ উপরে ফিরে যান](#table-of-contents)**


210.  ### How do you encode an URL

      The encodeURI() function is used to encode complete URI which has special characters except (, / ? : @ & = + $ #) characters.

      ```javascript
      var uri = "https://mozilla.org/?x=шеллы";
      var encoded = encodeURI(uri);
      console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
      ```

      **[⬆ Back to Top](#table-of-contents)**
### URL কোডিং কিভাবে করতে হয়

`encodeURI()` ফাংশনটি ব্যবহার হয় পূর্ণ URL কোড করতে, যেখানে বিশেষ অক্ষরগুলি (, / ? : @ & = + $ #) এই ক্যারাক্টারগুলির বাদে অন্যান্য সকল ক্যারাক্টারগুলি কোড হয়।

```javascript
var uri = "https://mozilla.org/?x=шеллы";
var encoded = encodeURI(uri);
console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
```

211.  ### How do you decode an URL

      The decodeURI() function is used to decode a Uniform Resource Identifier (URI) previously created by encodeURI().

      ```javascript
      var uri = "https://mozilla.org/?x=шеллы";
      var encoded = encodeURI(uri);
      console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
      try {
        console.log(decodeURI(encoded)); // "https://mozilla.org/?x=шеллы"
      } catch (e) {
        // catches a malformed URI
        console.error(e);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

### URL ডিকোডিং কিভাবে করতে হয়

`decodeURI()` ফাংশনটি ব্যবহার হয় একটি Uniform Resource Identifier (URI), যা আগে `encodeURI()` দ্বারা তৈরি করা হয়েছে, টি ডিকোড করতে।

```javascript
var uri = "https://mozilla.org/?x=шеллы";
var encoded = encodeURI(uri);
console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
try {
  console.log(decodeURI(encoded)); // "https://mozilla.org/?x=шеллы"
} catch (e) {
  // catches a malformed URI
  console.error(e);
}
```
212.  ### How do you print the contents of web page

      The window object provided a print() method which is used to print the contents of the current window. It opens a Print dialog box which lets you choose between various printing options. Let's see the usage of print method in an example,

      ```html
      <input type="button" value="Print" onclick="window.print()" />
      ```

      **Note:** In most browsers, it will block while the print dialog is open.

      **[⬆ Back to Top](#table-of-contents)**
### ওয়েব পৃষ্ঠার কনটেন্ট মুদ্রণ কিভাবে করতে হয়

`window` অবজেক্টটি একটি `print()` মেথড সরবরাহ করে যা বর্তমান উইন্ডোর কনটেন্টটি মুদ্রণ করতে ব্যবহৃত হয়। এটি একটি প্রিন্ট ডায়ালগ বক্স খোলে যা আপনাকে বিভিন্ন মুদ্রণ অপশন মধ্যে চয়ন করতে দেয়। একটি উদাহরণে প্রিন্ট মেথডের ব্যবহার দেখা যাক,

```html
<input type="button" value="Print" onclick="window.print()" />
```
**মন্তব্য:** 
            মূল্যবান ব্রাউজারগুলিতে, এটি প্রিন্ট ডায়ালগ খোলা থাকলে ব্লক করবে।

213.  ### What is the difference between uneval and eval

      The `uneval` function returns the source of a given object; whereas the `eval` function does the opposite, by evaluating that source code in a different memory area. Let's see an example to clarify the difference,

      ```javascript
      var msg = uneval(function greeting() {
        return "Hello, Good morning";
      });
      var greeting = eval(msg);
      greeting(); // returns "Hello, Good morning"
      ```

      **[⬆ Back to Top](#table-of-contents)**

### `uneval` এবং `eval` মধ্যে পার্থক্য কী

`uneval` ফাংশনটি একটি প্রদত্ত অবজেক্টের উৎস ফিরিয়ে দেয়; কিন্তু `eval` ফাংশনটি এই উৎস কোডটি একটি পৃথক মেমরি এরিয়ায় মূল্যায়ন করে। পার্থক্য বুঝাতে, নিম্নলিখিত উদাহরণটি দেখুন,

```javascript
var msg = uneval(function greeting() {
  return "Hello, Good morning";
});
var greeting = eval(msg);
greeting(); // returns "Hello, Good morning"
```
214.  ### What is an anonymous function

      An anonymous function is a function without a name! Anonymous functions are commonly assigned to a variable name or used as a callback function. The syntax would be as below,

      ```javascript
      function (optionalParameters) {
        //do something
      }

      const myFunction = function(){ //Anonymous function assigned to a variable
        //do something
      };

      [1, 2, 3].map(function(element){ //Anonymous function used as a callback function
        //do something
      });
      ```

      Let's see the above anonymous function in an example,

      ```javascript
      var x = function (a, b) {
        return a * b;
      };
      var z = x(5, 10);
      console.log(z); // 50
      ```

      **[⬆ Back to Top](#table-of-contents)**
### অজ্ঞাত ফাংশন কী

একটি অজ্ঞাত ফাংশন হলো একটি নাম ছাড়া ফাংশন! অজ্ঞাত ফাংশনগুলি সাধারিতঃ একটি ভেরিয়েবল নামে অ্যাসাইন করা হয় বা কলব্যাক ফাংশন হিসেবে ব্যবহৃত হয়। এর সিনট্যাক্স নিম্নলিখিত,

```javascript
function (optionalParameters) {
  // কিছু করুন
}

const myFunction = function(){ // একটি ভেরিয়েবলে অজ্ঞাত ফাংশন অ্যাসাইন করা হয়েছে
  // কিছু করুন
};

[1, 2, 3].map(function(element){ // একটি কলব্যাক ফাংশন হিসেবে ব্যবহৃত অজ্ঞাত ফাংশন
  // কিছু করুন
});
```
215.  ### What is the precedence order between local and global variables

      A local variable takes precedence over a global variable with the same name. Let's see this behavior in an example.

      ```javascript
      var msg = "Good morning";
      function greeting() {
        msg = "Good Evening";
        console.log(msg); // Good Evening
      }
      greeting();
      ```

      **[⬆ Back to Top](#table-of-contents)**
### লোকাল এবং গ্লোবাল ভ্যারিয়েবলের মধ্যে প্রাধিকৃত্য ক্রম

একটি লোকাল ভ্যারিয়েবল একটি একই নামে গ্লোবাল ভ্যারিয়েবলের উপর প্রাধিকৃত্য নেয়। এই পৌরাণিকতা একটি উদাহরণে দেখা যাক।

```javascript
var msg = "Good morning";
function greeting() {
  msg = "Good Evening";
  console.log(msg); // Good Evening
}
greeting();
```
216.  ### What are javascript accessors

      ECMAScript 5 introduced javascript object accessors or computed properties through getters and setters. Getters uses the `get` keyword whereas Setters uses the `set` keyword.

      ```javascript
      var user = {
        firstName: "John",
        lastName: "Abraham",
        language: "en",
        get lang() {
          return this.language;
        },
        set lang(lang) {
          this.language = lang;
        },
      };
      console.log(user.lang); // getter access lang as en
      user.lang = "fr";
      console.log(user.lang); // setter used to set lang as fr
      ```

      **[⬆ Back to Top](#table-of-contents)**
### জাভাস্ক্রিপ্ট অ্যাক্সেসর

ECMAScript 5-এ জাভাস্ক্রিপ্ট অবজেক্ট অ্যাক্সেসর বা কম্পিউটেড প্রপার্টির মাধ্যমে গেটার এবং সেটার দ্বারা জাভাস্ক্রিপ্ট অবজেক্ট অ্যাক্সেসর তৈরি হয়েছিল। গেটার এর জন্য `get` কীওয়ার্ড ব্যবহার করা হয় যখন সেটার এর জন্য `set` কীওয়ার্ড ব্যবহার করা হয়।

```javascript
var user = {
  firstName: "John",
  lastName: "Abraham",
  language: "en",
  get lang() {
    return this.language;
  },
  set lang(lang) {
    this.language = lang;
  },
};
console.log(user.lang); // getter দ্বারা lang এর মান পাওয়া হচ্ছে en
user.lang = "fr";
console.log(user.lang); // setter ব্যবহার করে lang কে fr হিসেবে সেট করা হচ্ছে
```
217.  ### How do you define property on Object constructor

      The Object.defineProperty() static method is used to define a new property directly on an object, or modify an existing property on an object, and returns the object. Let's see an example to know how to define property,

      ```javascript
      const newObject = {};

      Object.defineProperty(newObject, "newProperty", {
        value: 100,
        writable: false,
      });

      console.log(newObject.newProperty); // 100

      newObject.newProperty = 200; // It throws an error in strict mode due to writable setting
      ```

      **[⬆ Back to Top](#table-of-contents)**
### অবজেক্ট কনস্ট্রাক্টরে প্রোপার্টি সংজ্ঞায়িত করতে

Object.defineProperty() স্ট্যাটিক মেথডটি একটি নতুন প্রোপার্টি সংজ্ঞায়িত করতে বা একটি বিদ্যমান প্রোপার্টি উপর সরানোর জন্য ব্যবহৃত হয়, এবং অবজেক্টটি রিটার্ন করে। কিভাবে একটি প্রোপার্টি সংজ্ঞায়িত করতে হয় তা জানতে একটি উদাহরণ দেখা যাক,

```javascript
const newObject = {};

Object.defineProperty(newObject, "newProperty", {
  value: 100,
  writable: false,
});

console.log(newObject.newProperty); // 100

newObject.newProperty = 200; // writable সেটিং এর জন্য স্ট্রিক্ট মোডে একটি ত্রুটি তৈরি করে
```
218.  ### What is the difference between get and defineProperty

      Both have similar results until unless you use classes. If you use `get` the property will be defined on the prototype of the object whereas using `Object.defineProperty()` the property will be defined on the instance it is applied to.

      **[⬆ Back to Top](#table-of-contents)**
### `get` এবং `defineProperty` মধ্যে পার্থক্য

উভয়ই অনুভব করা হয় পরিমিতির দৃষ্টিকোণ হতে, একবার যদি আপনি ক্লাস ব্যবহার করেন। যদি আপনি `get` ব্যবহার করেন তবে প্রপার্টি অবজেক্টের প্রোটোটাইপে সংজ্ঞায়িত হবে, অন্যথায় `Object.defineProperty()` ব্যবহার করার সময় প্রপার্টি তার উপর সংজ্ঞায়িত হবে যা এটি প্রয়োগ করা হয়েছে।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

219.  ### What are the advantages of Getters and Setters

      Below are the list of benefits of Getters and Setters,

      1.  They provide simpler syntax
      2.  They are used for defining computed properties, or accessors in JS.
      3.  Useful to provide equivalence relation between properties and methods
      4.  They can provide better data quality
      5.  Useful for doing things behind the scenes with the encapsulated logic.

      **[⬆ Back to Top](#table-of-contents)**
### গেটার এবং সেটারের সুবিধাগুলি

নিম্নলিখিত হলো গেটার এবং সেটারের সুবিধাগুলির তালিকা,

1.  এগুলি সহজ সিনট্যাক্স সরবরাহ করে
2.  এগুলি JS-এ কম্পিউটেড প্রোপার্টি বা অ্যাক্সেসর সংজ্ঞায়িত করার জন্য ব্যবহৃত হয়
3.  প্রোপার্টি এবং মেথডগুলির মধ্যে সমতা স্থাপনের জন্য দরকারী
4.  এগুলি ভাল ডেটা গুণগতি সরবরাহ করতে পারে
5.  এগুলি এনক্যাপসুলেটেড লজিক সাথে পিছিয়ে গেলের জন্য দরকারি

**[⬆ উপরে ফিরে যান](#table-of-contents)**

220.  ### Can I add getters and setters using defineProperty method

      Yes, You can use the `Object.defineProperty()` method to add Getters and Setters. For example, the below counter object uses increment, decrement, add and subtract properties,

      ```javascript
      var obj = { counter: 0 };

      // Define getters
      Object.defineProperty(obj, "increment", {
        get: function () {
          this.counter++;
        },
      });
      Object.defineProperty(obj, "decrement", {
        get: function () {
          this.counter--;
        },
      });

      // Define setters
      Object.defineProperty(obj, "add", {
        set: function (value) {
          this.counter += value;
        },
      });
      Object.defineProperty(obj, "subtract", {
        set: function (value) {
          this.counter -= value;
        },
      });

      obj.add = 10;
      obj.subtract = 5;
      console.log(obj.increment); //6
      console.log(obj.decrement); //5
      ```

      **[⬆ Back to Top](#table-of-contents)**

### কি Object.defineProperty() মেথড ব্যবহার করে গেটার এবং সেটার যোগ করা যায়?

হ্যাঁ, আপনি `Object.defineProperty()` মেথড ব্যবহার করে গেটার এবং সেটার যোগ করতে পারেন। উদাহরণস্বরূপ, নিচের কাউন্টার অবজেক্টটি ইনক্রিমেন্ট, ডিক্রিমেন্ট, যোগ এবং বিয়োগ প্রোপার্টিগুলি ব্যবহার করে,

```javascript
var obj = { counter: 0 };

// গেটার ডিফাইন করুন
Object.defineProperty(obj, "increment", {
  get: function () {
    this.counter++;
  },
});
Object.defineProperty(obj, "decrement", {
  get: function () {
    this.counter--;
  },
});

// সেটার ডিফাইন করুন
Object.defineProperty(obj, "add", {
  set: function (value) {
    this.counter += value;
  },
});
Object.defineProperty(obj, "subtract", {
  set: function (value) {
    this.counter -= value;
  },
});

obj.add = 10;
obj.subtract = 5;
console.log(obj.increment); // 6
console.log(obj.decrement); // 5
```
221.  ### What is the purpose of switch-case

      The switch case statement in JavaScript is used for decision making purposes. In a few cases, using the switch case statement is going to be more convenient than if-else statements. The syntax would be as below,

      ```javascript
      switch (expression)
      {
          case value1:
              statement1;
              break;
          case value2:
              statement2;
              break;
          .
          .
          case valueN:
              statementN;
              break;
          default:
              statementDefault;
      }
      ```

      The above multi-way branch statement provides an easy way to dispatch execution to different parts of code based on the value of the expression.

      **[⬆ Back to Top](#table-of-contents)**
### সুইচ-কেস এর উদ্দেশ্য কি?

জাভাস্ক্রিপ্টে সুইচ-কেস স্টেটমেন্টটি নির্ধারণ নেওয়ার জন্য ব্যবহৃত হয় নির্ধারণ নেওয়ার উদ্দেশ্যে। কিছু ক্ষেত্রে, সুইচ-কেস স্টেটমেন্ট ব্যবহার করা ইফ-এল্স স্টেটমেন্টগুলির চেয়ে সুবিধাজনক হতে পারে। নীচের সিনট্যাক্সটির মত,

```javascript
switch (expression)
{
    case value1:
        statement1;
        break;
    case value2:
        statement2;
        break;
    .
    .
    case valueN:
        statementN;
        break;
    default:
        statementDefault;
}
```
উপরের এই মাল্টি-উয়ে ব্র্যাঞ্চ স্টেটমেন্টটি একটি একক কোডের বিভিন্ন অংশে প্রয়োজনের উপরে অনুভূতি দেয় যা অভিবিন্ন মান দ্বারা কোডের বিভিন্ন অংশে এক্সিকিউশন প্রেরণ করার সহজ উপায় দেয়।

222.  ### What are the conventions to be followed for the usage of switch case

      Below are the list of conventions should be taken care,

      1.  The expression can be of type either number or string.
      2.  Duplicate values are not allowed for the expression.
      3.  The default statement is optional. If the expression passed to switch does not match with any case value then the statement within default case will be executed.
      4.  The break statement is used inside the switch to terminate a statement sequence.
      5.  The break statement is optional. But if it is omitted, the execution will continue on into the next case.

      **[⬆ Back to Top](#table-of-contents)**

### সুইচ-কেস ব্যবহারের জন্য কি ধরণের শৃঙ্খলা অনুসরণ করা উচিত?

নীচে কিছু শৃঙ্খলা হওয়া উচিত সুইচ-কেস ব্যবহারের জন্য,

1. এক্সপ্রেশন হতে পারে সংখ্যা বা স্ট্রিং ধরনের যেকোনো একটি।
2. এক্সপ্রেশনে ডুপ্লিকেট মান অনুমোদিত নয়।
3. ডিফল্ট স্টেটমেন্টটি ঐচ্ছিক। যদি সুইচটিতে পাঠানো এক্সপ্রেশন কোনও কেস মানের সাথে মিলছে না, তবে ডিফল্ট কেসের মধ্যে স্টেটমেন্টটি অমলের হবে।
4. সুইচ এর মধ্যে ব্রেক স্টেটমেন্টটি একটি স্টেটমেন্ট সিকোয়েন্স সমাপ্ত করতে ব্যবহৃত হয়।
5. ব্রেক স্টেটমেন্টটি ঐচ্ছিক। কিন্তু যদি এটি অমিট করা হয়, তবে কার্যক্রম পরবর্তী কেসে চলবে।

**[⬆ উপরে ফিরে যান](#table-of-contents)**


223.  ### What are primitive data types

      A primitive data type is data that has a primitive value (which has no properties or methods). There are 7 types of primitive data types.

      1.  string
      2.  number
      3.  boolean
      4.  null
      5.  undefined
      6.  bigint
      7.  symbol

      **[⬆ Back to Top](#table-of-contents)**
### কি হলো প্রাইমিটিভ ডাটা টাইপ?

একটি প্রাইমিটিভ ডাটা টাইপ হলো যে ডাটা একটি প্রাইমিটিভ মান রাখে (যা কোনও বৈশিষ্ট্য বা মেথড নেই)। একটি ভাষায় ৭ টি প্রাইমিটিভ ডাটা টাইপ থাকতে পারে।

1. string
2. number
3. boolean
4. null
5. undefined
6. bigint
7. symbol

**[⬆ উপরে ফিরে যান](#table-of-contents)**

224.  ### What are the different ways to access object properties

      There are 3 possible ways for accessing the property of an object.

      1.  **Dot notation:** It uses dot for accessing the properties

      ```javascript
      objectName.property;
      ```

      1.  **Square brackets notation:** It uses square brackets for property access

      ```javascript
      objectName["property"];
      ```

      1.  **Expression notation:** It uses expression in the square brackets

      ```javascript
      objectName[expression];
      ```

      **[⬆ Back to Top](#table-of-contents)**

### অবজেক্ট প্রোপার্টি অ্যাক্সেস করার বিভিন্ন উপায়

একটি অবজেক্টের প্রোপার্টি অ্যাক্সেস করার জন্য ৩টি সম্ভাব্য উপায় আছে।

1. **ডট নোটেশন:** এটি প্রোপার্টি অ্যাক্সেস করার জন্য ডট ব্যবহার করে

```javascript
   অবজেক্টের_নাম.প্রোপার্টি;
```
**স্কোয়ার ব্র্যাকেটস নোটেশন:** এটি প্রোপার্টি অ্যাক্সেস করার জন্য স্কোয়ার ব্র্যাকেট ব্যবহার করে
```javascript
অবজেক্টের_নাম["প্রোপার্টি"];
```
**এক্সপ্রেশন নোটেশন:** এটি স্কোয়ার ব্র্যাকেটে এক্সপ্রেশন ব্যবহার করে

```javascript
অবজেক্টের_নাম[এক্সপ্রেশন];
```

225.  ### What are the function parameter rules

      JavaScript functions follow below rules for parameters,

      1.  The function definitions do not specify data types for parameters.
      2.  Do not perform type checking on the passed arguments.
      3.  Do not check the number of arguments received.
          i.e, The below function follows the above rules,

      ```javascript
      function functionName(parameter1, parameter2, parameter3) {
        console.log(parameter1); // 1
      }
      functionName(1);
      ```

      **[⬆ Back to Top](#table-of-contents)**
### ফাংশন প্যারামিটার নিয়মাবলী

জাভাস্ক্রিপ্ট ফাংশনগুলি নিম্নলিখিত নিয়মাবলী অনুসরণ করে প্যারামিটারের জন্য,

1. ফাংশন ডিফিনিশনগুলি প্যারামিটারগুলির জন্য ডেটা টাইপ সুনির্দিষ্ট করে না।
2. পাস করা আর্গুমেন্টগুলির উপর টাইপ চেকিং করে না।
3. প্রাপ্ত আর্গুমেন্টগুলির সংখ্যা চেক করে না।
   অর্থাৎ, নিচের ফাংশনটি উপরে উল্লেখিত নিয়মাগুলি অনুসরণ করে,

```javascript
function ফাংশনের_নাম(প্যারামিটার1, প্যারামিটার2, প্যারামিটার3) {
  console.log(প্যারামিটার1); // 1
}
ফাংশনের_নাম(1);
```

226.  ### What is an error object

      An error object is a built in error object that provides error information when an error occurs. It has two properties: name and message. For example, the below function logs error details,

      ```javascript
      try {
        greeting("Welcome");
      } catch (err) {
        console.log(err.name + "<br>" + err.message);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**
### এরর অবজেক্ট

একটি এরর অবজেক্ট হলো একটি প্রবেশিত এরর অবজেক্ট যা এরর ঘটতে সময় তথ্য প্রদান করে। এটির দুটি গুলি প্রপার্টি আছে: name এবং message। উদাহরণস্বরূপ, নিচের ফাংশনটি এরর বিবরণ লগ করে,

```javascript
try {
  greeting("Welcome");
} catch (err) {
  console.log(err.name + "<br>" + err.message);
}
```
227.  ### When you get a syntax error

      A SyntaxError is thrown if you try to evaluate code with a syntax error. For example, the below missing quote for the function parameter throws a syntax error

      ```javascript
      try {
        eval("greeting('welcome)"); // Missing ' will produce an error
      } catch (err) {
        console.log(err.name);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**
### সিনট্যাক্স এরর

একটি সিনট্যাক্স এরর প্রকাশ হয় যদি আপনি কোড বিশ্লেষণ করতে চান এবং সিনট্যাক্স এরর থাকে। উদাহরণস্বরূপ, নীচের ফাংশন প্যারামিটারের জন্য কোট হারিয়ে গিয়ে একটি সিনট্যাক্স এরর তৈরি করে

```javascript
try {
  eval("greeting('welcome)"); // Missing ' will produce an error
} catch (err) {
  console.log(err.name);
}
```

228.  ### What are the different error names from error object

      There are 6 different types of error names returned from error object,
      | Error Name | Description |
      |---- | ---------
      | EvalError | An error has occurred in the eval() function |
      | RangeError | An error has occurred with a number "out of range" |
      | ReferenceError | An error due to an illegal reference|
      | SyntaxError | An error due to a syntax error|
      | TypeError | An error due to a type error |
      | URIError | An error due to encodeURI() |

      **[⬆ Back to Top](#table-of-contents)**
### এরর অবজেক্ট থেকে বিভিন্ন এরর নেম

এরর অবজেক্ট থেকে 6 ধরণের এরর নেম প্রাপ্ত হয়,

| এরর নেম     | বর্ণনা                                         |
| ------------ | --------------------------------------------- |
| EvalError    | eval() ফাংশনে একটি এরর হয়েছে             |
| RangeError   | একটি সংখ্যা "সীমার বাইরে" এরর হয়েছে       |
| ReferenceError | একটি অবৈধ রেফারেন্সের কারণে এরর হয়েছে   |
| SyntaxError  | সিনট্যাক্স এররের কারণে এরর হয়েছে         |
| TypeError    | টাইপ এররের কারণে এরর হয়েছে               |
| URIError     | encodeURI() এর জন্য এরর হয়েছে                |

**[⬆ উপরে ফিরে যান](#table-of-contents)**

229.  ### What are the various statements in error handling

      Below are the list of statements used in an error handling,

      1.  **try:** This statement is used to test a block of code for errors
      2.  **catch:** This statement is used to handle the error
      3.  **throw:** This statement is used to create custom errors.
      4.  **finally:** This statement is used to execute code after try and catch regardless of the result.

      **[⬆ Back to Top](#table-of-contents)**

### এরর হ্যান্ডলিং এ বিভিন্ন স্টেটমেন্টস

নিচে এরর হ্যান্ডলিং এ ব্যবহৃত স্টেটমেন্টসের তালিকা,

1.  **try:** এটি কোড ব্লকটি ত্রুটির জন্য টেস্ট করতে ব্যবহৃত হয়
2.  **catch:** এটি এরর হ্যান্ডল করতে ব্যবহৃত হয়
3.  **throw:** এটি কাস্টম এরর তৈরি করতে ব্যবহৃত হয়
4.  **finally:** এটি try এবং catch এর পরে কোডটি সম্পন্ন হওয়ার পরে ব্যবহৃত হয়, যেকোন ফলাফলের মোকাবেলায় ব্যবহৃত হয়।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

230.  ### What are the two types of loops in javascript

      1.  **Entry Controlled loops:** In this kind of loop type, the test condition is tested before entering the loop body. For example, For Loop and While Loop comes under this category.
      2.  **Exit Controlled Loops:** In this kind of loop type, the test condition is tested or evaluated at the end of the loop body. i.e, the loop body will execute at least once irrespective of test condition true or false. For example, do-while loop comes under this category.

      **[⬆ Back to Top](#table-of-contents)**
### JavaScript-এ দুটি প্রকারের লুপ

1.  **এন্ট্রি কন্ট্রোলড লুপসমূহ (Entry Controlled Loops):** এই ধরণের লুপে, লুপ বডির ভেতরে ঢুকার আগে পরীক্ষা শর্ত পরীক্ষা করা হয়। এই ক্যাটেগরিতে For Loop এবং While Loop পড়ে।
2.  **এক্সিট কন্ট্রোলড লুপসমূহ (Exit Controlled Loops):** এই ধরণের লুপে, টেস্ট কন্ডিশন লুপ বডির শেষে পরীক্ষা বা মূল্যায়ন করা হয়। অর্থাৎ, লুপ বডি কমপক্ষে একবার অবশ্যই চলবে, তো পরীক্ষা শর্ত সত্য বা মিথ্যা হোক না কেন। এই ক্যাটেগরিতে do-while লুপ পড়ে।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

231.  ### What is nodejs

      Node.js is a server-side platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. It is an event-based, non-blocking, asynchronous I/O runtime that uses Google's V8 JavaScript engine and libuv library.

      **[⬆ Back to Top](#table-of-contents)**
### নোড.জেএস (Node.js)

নোড.জেএস হলো একটি সার্ভার-সাইড প্ল্যাটফর্ম যা চ্রোমের জাভাস্ক্রিপ্ট রানটাইমে ভিত্তি করে, যা দ্রুত এবং স্কেলেবল নেটওয়ার্ক অ্যাপ্লিকেশন সহজে তৈরি করতে সাহায্য করে। এটি ইভেন্ট-ভিত্তিক, নন-ব্লকিং, অসিঞ্চ্রোনাস I/O রানটাইম যা গুগলের V8 জাভাস্ক্রিপ্ট ইঞ্জিন এবং লিবউভ লাইব্রেরি ব্যবহার করে।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

232.  ### What is an Intl object

      The Intl object is the namespace for the ECMAScript Internationalization API, which provides language sensitive string comparison, number formatting, and date and time formatting. It provides access to several constructors and language sensitive functions.

      **[⬆ Back to Top](#table-of-contents)**
### ইন্ট্রন্যাশনালিজেশন (Intl) অবজেক্ট

ইন্ট্রন্যাশনালিজেশন (Intl) অবজেক্ট হলো ECMAScript ইন্টারন্যাশনালাইজেশন API এর নেমস্পেস, যা ভাষা-সংবেদনশীল স্ট্রিং তুলনা, নাম্বার ফরম্যাটিং এবং ডেট এবং টাইম ফরম্যাটিং সরবরাহ করে। এটি বিরাট সংখ্যক কনস্ট্রাক্টর এবং ভাষা-সংবেদনশীল ফাংশনে অ্যাক্সেস প্রদান করে।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

233.  ### How do you perform language specific date and time formatting

      You can use the `Intl.DateTimeFormat` object which is a constructor for objects that enable language-sensitive date and time formatting. Let's see this behavior with an example,

      ```javascript
      var date = new Date(Date.UTC(2019, 07, 07, 3, 0, 0));
      console.log(new Intl.DateTimeFormat("en-GB").format(date)); // 07/08/2019
      console.log(new Intl.DateTimeFormat("en-AU").format(date)); // 07/08/2019
      ```

      **[⬆ Back to Top](#table-of-contents)**
### ভাষা-সংবেদনশীল ডেট এবং টাইম ফরম্যাটিং

ভাষা-সংবেদনশীল ডেট এবং টাইম ফরম্যাটিং করতে আপনি `Intl.DateTimeFormat` অবজেক্ট ব্যবহার করতে পারেন, যা একটি ভাষা-সংবেদনশীল ডেট এবং টাইম ফরম্যাটিং সক্ষম করার জন্য কনস্ট্রাক্টর। নিচে একটি উদাহরণ দেখা হয়েছে,

```javascript
var date = new Date(Date.UTC(2019, 07, 07, 3, 0, 0));
console.log(new Intl.DateTimeFormat("en-GB").format(date)); // 07/08/2019
console.log(new Intl.DateTimeFormat("en-AU").format(date)); // 07/08/2019
```
234.  ### What is an Iterator

      An iterator is an object which defines a sequence and a return value upon its termination. It implements the Iterator protocol with a `next()` method which returns an object with two properties: `value` (the next value in the sequence) and `done` (which is true if the last value in the sequence has been consumed).

      **[⬆ Back to Top](#table-of-contents)**
### ইটারেটর

একটি ইটারেটর হলো একটি অবজেক্ট যা একটি ক্রম এবং এর সমাপ্তি হতে একটি মান প্রদান করে। এটি একটি `next()` মেথড দিয়ে Iterator প্রোটোকল ইমপ্লিমেন্ট করে যা একটি অবজেক্ট রিটার্ন করে যা দুটি প্রোপার্টি থাকে: `value` (ক্রমবর্ধমান মান) এবং `done` (যদি ক্রমবর্ধমান মান চূড়ান্ত হয়ে যায় তাহলে true)।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

235.  ### How does synchronous iteration works

      Synchronous iteration was introduced in ES6 and it works with below set of components,

      **Iterable:** It is an object which can be iterated over via a method whose key is Symbol.iterator.
      **Iterator:** It is an object returned by invoking `[Symbol.iterator]()` on an iterable. This iterator object wraps each iterated element in an object and returns it via `next()` method one by one.
      **IteratorResult:** It is an object returned by `next()` method. The object contains two properties; the `value` property contains an iterated element and the `done` property determines whether the element is the last element or not.

      Let's demonstrate synchronous iteration with an array as below,

      ```javascript
      const iterable = ["one", "two", "three"];
      const iterator = iterable[Symbol.iterator]();
      console.log(iterator.next()); // { value: 'one', done: false }
      console.log(iterator.next()); // { value: 'two', done: false }
      console.log(iterator.next()); // { value: 'three', done: false }
      console.log(iterator.next()); // { value: 'undefined, done: true }
      ```

      **[⬆ Back to Top](#table-of-contents)**
### সমকালিন ইটারেশনের কাজকরী

ES6-এ সমকালিন ইটারেশন প্রস্তুত করা হয়েছিল এবং এটি নিম্নোক্ত উপাদানের সাথে কাজ করে,

- **ইটারেবল:** এটি একটি অবজেক্ট যা Symbol.iterator এর কী দিয়ে যাত্রা করা যায়।
- **ইটারেটর:** এটি একটি অবজেক্ট যা একটি ইটারেবলে `[Symbol.iterator]()` কে ইঙ্কোক করলে প্রদান হয়। এই ইটারেটর অবজেক্টটি প্রতি ইটারেটেড এলিমেন্টকে একটি অবজেক্টে রেখে এবং এটি ব্যবহার করে `next()` মেথডের মাধ্যমে একটি একটি রিটার্ন করে।
- **ইটারেটর রেজাল্ট:** এটি `next()` মেথড দ্বারা প্রদান করা হয়। এই অবজেক্টটি দুটি প্রোপার্টি ধারণ করে; `value` প্রোপার্টিতে একটি ইটারেটেড এলিমেন্ট থাকে এবং `done` প্রোপার্টি ধারণ করে এলিমেন্টটি শেষ এলিমেন্ট কি না তা নির্ধারণ করে।

নিচে একটি অ্যারের সাথে সমকালিন ইটারেশন দেখানো হয়েছে,

```javascript
const iterable = ["one", "two", "three"];
const iterator = iterable[Symbol.iterator]();
console.log(iterator.next()); // { value: 'one', done: false }
console.log(iterator.next()); // { value: 'two', done: false }
console.log(iterator.next()); // { value: 'three', done: false }
console.log(iterator.next()); // { value: 'undefined, done: true }
```
236.  ### What is an event loop

      The event loop is a process that continuously monitors both the call stack and the event queue and checks whether or not the call stack is empty. If the call stack is empty and there are pending events in the event queue, the event loop dequeues the event from the event queue and pushes it to the call stack. The call stack executes the event, and any additional events generated during the execution are added to the end of the event queue.

      **Note:** The event loop allows Node.js to perform non-blocking I/O operations, even though JavaScript is single-threaded, by offloading operations to the system kernel whenever possible. Since most modern kernels are multi-threaded, they can handle multiple operations executing in the background.

      **[⬆ Back to Top](#table-of-contents)**
### ইভেন্ট লুপ

ইভেন্ট লুপ হলো একটি প্রক্রিয়া যা ধারণ করে কল স্ট্যাক এবং ইভেন্ট কিউ উভয়ই নিয়মিতভাবে মনিটর করে এবং চেক করে কল স্ট্যাক কি খালি আছে কি না। যদি কল স্ট্যাক খালি থাকে এবং ইভেন্ট কিউতে মুলতবি ইভেন্ট থাকে, তবে ইভেন্ট লুপটি ইভেন্ট কিউ থেকে ইভেন্ট বের করে এবং এটি কল স্ট্যাকে ঢুকিয়ে দেয়। কল স্ট্যাক ইভেন্টটি সম্পাদনা করে এবং সম্পাদনা করার পর এর সম্প্রচারের সময় জন্য আমদানি ইভেন্টগুলি ইভেন্ট কিউর শেষে যোগ করা হয়।

**নোট:** ইভেন্ট লুপ দেওয়ায় Node.js কে নন-ব্লকিং I/O অপারেশন করতে অনুমতি দেয়, তবে JavaScript একক থ্রেডে চলতে হবে, যা সম্ভাবনামতো ব্লকিং I/O অপারেশন করতে বাধ্য করে না, সিস্টেম কার্নেলে যখন সম্ভাবনামতো অপারেশন অফলোড হয়ে যায়। কারণ অধিকাংশ আধুনিক কার্নেলগুলি মাল্টি-থ্রেডেড হয়ে থাকে এবং এগুলি পৃষ্ঠভূমির অপারেশন সম্পাদন করতে পারে।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

237.  ### What is call stack

      Call Stack is a data structure for javascript interpreters to keep track of function calls(creates execution context) in the program. It has two major actions,

      1.  Whenever you call a function for its execution, you are pushing it to the stack.
      2.  Whenever the execution is completed, the function is popped out of the stack.

      Let's take an example and it's state representation in a diagram format

      ```javascript
      function hungry() {
        eatFruits();
      }
      function eatFruits() {
        return "I'm eating fruits";
      }

      // Invoke the `hungry` function
      hungry();
      ```

      The above code processed in a call stack as below,

      1.  Add the `hungry()` function to the call stack list and execute the code.
      2.  Add the `eatFruits()` function to the call stack list and execute the code.
      3.  Delete the `eatFruits()` function from our call stack list.
      4.  Delete the `hungry()` function from the call stack list since there are no items anymore.

      ![Screenshot](images/call-stack.png)

      **[⬆ Back to Top](#table-of-contents)**
### কল স্ট্যাক

কল স্ট্যাক হলো জাভাস্ক্রিপ্ট ইন্টারপ্রিটারের জন্য একটি ডেটা স্ট্রাকচার, যা প্রোগ্রামে ফাংশন কলগুলির স্থানান্তর রেখে রাখতে হয় (এক্সিকিউশন কন্টেক্সট তৈরি করে)। এর দুইটি প্রধান কার্য আছে,

1. যখন আপনি একটি ফাংশনকে এর সম্পাদনায় কল করেন, তখন আপনি এটি স্ট্যাকে পুশ করছেন।
2. সম্পাদনা সম্পন্ন হলে, ফাংশনটি স্ট্যাক থেকে পপ হয়ে যাচ্ছে।

নিচে একটি উদাহরণ এবং এর ডায়াগ্রাম ফরম্যাটে অবস্থা প্রতিষ্ঠানের দেখানো হয়েছে

```javascript
function hungry() {
  eatFruits();
}
function eatFruits() {
  return "I'm eating fruits";
}

// হাংরি ফাংশনটি কল করুন
hungry();
```
উপরের কোডটি কল স্ট্যাকে নিম্নলিখিত ভাবে প্রসেস হয়েছে,

## hungry() ফাংশনটি কল স্ট্যাক তালিকায় যোগ করুন এবং কোডটি সম্পাদনা করুন।
## eatFruits() ফাংশনটি কল স্ট্যাক তালিকায় যোগ করুন এবং কোডটি সম্পাদনা করুন।
## আমাদের কল স্ট্যাক তালিকা থেকে eatFruits() ফাংশনটি মুছে ফেলুন।
## কোনো আইটেম নেই তাই hungry() ফাংশনটি কল স্ট্যাক তালিকা থেকে মুছে ফেলুন।

238.  ### What is an event queue

      The event queue follows the queue data structure. It stores async callbacks to be added to the call stack. It is also known as the Callback Queue or Macrotask Queue.

      Whenever the call stack receives an async function, it is moved into the Web API. Based on the function, Web API executes it and awaits the result. Once it is finished, it moves the callback into the event queue (the callback of the promise is moved into the microtask queue).

      The event loop constantly checks whether or not the call stack is empty. Once the call stack is empty and there is a callback in the event queue, the event loop moves the callback into the call stack. But if there is a callback in the microtask queue as well, it is moved first. The microtask queue has a higher priority than the event queue.

      **[⬆ Back to Top](#table-of-contents)**
### ইভেন্ট কিউ

ইভেন্ট কিউটি কিউ ডেটা স্ট্রাকচার অনুসরণ করে। এটি কল স্ট্যাকে যোগ করা যাবে না কারণ এটি অসিঙ্ক্রোনাস কলব্যাকগুলির জন্য। এটিকে একেবারে কল স্ট্যাকে যোগ করতে এটি কল স্ট্যাকের মধ্যে একটি প্রকার স্থানান্তর বা এড করতে হয় (প্রমিসের কলব্যাকটির ক্ষেত্রে এটি মাইক্রোটাস্ক কিউতে এড হয়)।

যখন কল স্ট্যাকটি একটি অ্যাসিঙ্ক ফাংশন পেয়েছে, তখন এটি ওয়েব এপিআইতে নিযুক্ত হয়েছে। ওয়েব এপিআই এটি সম্পাদনা করতে এবং ফলাফলের জন্য অপেক্ষা করতে বলছে। এটি শেষ হলে, সম্পাদনা সম্পন্ন হলে কলব্যাকটি ইভেন্ট কিউতে সরিয়ে দেওয়া হয় (প্রমিসের কলব্যাকটি মাইক্রোটাস্ক কিউতে সরিয়ে যাওয়া হয়)।

ইভেন্ট লুপ সততায় পরীক্ষা করে যে কল স্ট্যাক খালি কিনা। একবার কল স্ট্যাক খালি হলে এবং ইভেন্ট কিউতে একটি কলব্যাক থাকলে, ইভেন্ট লুপ কলব্যাকটি কল স্ট্যাকে সরিয়ে দেয়। তবে যদি মাইক্রোটাস্ক কিউতে একটি কলব্যাক থাকে, তাদের প্রথমে সরিয়ে নেয়। মাইক্রোটাস্ক কিউটি ইভেন্ট কিউর চেয়ে উচ্চ অধিকারিতা রাখে।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

239.  ### What is a decorator

      A decorator is an expression that evaluates to a function and that takes the target, name, and decorator descriptor as arguments. Also, it optionally returns a decorator descriptor to install on the target object. Let's define admin decorator for user class at design time,

      ```javascript
      function admin(isAdmin) {
         return function(target) {
             target.isAdmin = isAdmin;
         }
      }

      @admin(true)
      class User() {
      }
      console.log(User.isAdmin); //true

       @admin(false)
       class User() {
       }
       console.log(User.isAdmin); //false
      ```

      **[⬆ Back to Top](#table-of-contents)**
### ডেকোরেটর

একটি ডেকোরেটর একটি ফাংশনে যা একটি ফাংশনে যা লক্ষ্য, নাম এবং ডেকোরেটর ডেসক্রিপ্টর বিশ্লেষণ হিসেবে কর্ম করে। এটি ঐচ্ছিকভাবে লক্ষ্য অবজেক্টে ইনস্টল করতে একটি ডেকোরেটর ডেসক্রিপ্টর কে ফিরিয়ে দেয়। ডিজাইন টাইমে ব্যবহারকারী ক্লাসের জন্য এডমিন ডেকোরেটর সংজ্ঞায়িত করা হয়,

```javascript
function admin(isAdmin) {
   return function(target) {
       target.isAdmin = isAdmin;
   }
}

@admin(true)
class User() {
}
console.log(User.isAdmin); //true

 @admin(false)
 class User() {
 }
 console.log(User.isAdmin); //false
```
240.  ### What are the properties of Intl object

      Below are the list of properties available on Intl object,

      1.  **Collator:** These are the objects that enable language-sensitive string comparison.
      2.  **DateTimeFormat:** These are the objects that enable language-sensitive date and time formatting.
      3.  **ListFormat:** These are the objects that enable language-sensitive list formatting.
      4.  **NumberFormat:** Objects that enable language-sensitive number formatting.
      5.  **PluralRules:** Objects that enable plural-sensitive formatting and language-specific rules for plurals.
      6.  **RelativeTimeFormat:** Objects that enable language-sensitive relative time formatting.

      **[⬆ Back to Top](#table-of-contents)**
### Intl অবজেক্টের প্রোপার্টিস

নীচে রয়েছে Intl অবজেক্টের প্রোপার্টিগুলির তালিকা,

1. **Collator:** এগুলি ভাষা-সহায়ক স্ট্রিং তুলনা সক্ষম করার অবজেক্ট।
2. **DateTimeFormat:** এগুলি ভাষা-সহায়ক তারিখ এবং সময় বিন্যাস করার অবজেক্ট।
3. **ListFormat:** এগুলি ভাষা-সহায়ক তালিকা বিন্যাস করার অবজেক্ট।
4. **NumberFormat:** ভাষা-সহায়ক সংখ্যা বিন্যাস করার জন্য অবজেক্ট।
5. **PluralRules:** বহুভুজ সংখ্যা বিন্যাস এবং বহুভুজ সংবাদের জন্য ভাষা-সহায়ক নিয়ম অবজেক্ট।
6. **RelativeTimeFormat:** ভাষা-সহায়ক আপেক্ষিক সময় বিন্যাস করার জন্য অবজেক্ট।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

241.  ### What is an Unary operator

      The unary(+) operator is used to convert a variable to a number.If the variable cannot be converted, it will still become a number but with the value NaN. Let's see this behavior in an action.

      ```javascript
      var x = "100";
      var y = +x;
      console.log(typeof x, typeof y); // string, number

      var a = "Hello";
      var b = +a;
      console.log(typeof a, typeof b, b); // string, number, NaN
      ```

      **[⬆ Back to Top](#table-of-contents)**
### ইউনারি অপারেটর

ইউনারি(+) অপারেটরটি একটি ভ্যারিয়েবলকে একটি সংখ্যায় রূপান্তর করতে ব্যবহৃত হয়। ভ্যারিয়েবলটি রূপান্তর করা সম্ভব না হলে, এটি এখনো একটি সংখ্যা হয়ে যাবে কিন্তু মানটি NaN হবে। এই আচরণটি একটি উদাহরণে দেখা যাক।

```javascript
var x = "100";
var y = +x;
console.log(typeof x, typeof y); // string, number

var a = "Hello";
var b = +a;
console.log(typeof a, typeof b, b); // string, number, NaN
```
242.  ### How do you sort elements in an array

      The sort() method is used to sort the elements of an array in place and returns the sorted array. The example usage would be as below,

      ```javascript
      var months = ["Aug", "Sep", "Jan", "June"];
      months.sort();
      console.log(months); //  ["Aug", "Jan", "June", "Sep"]
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কিভাবে একটি অ্যারেতে উপাদানগুলি সাজানো হয়

sort() মেথডটি অ্যারের উপাদানগুলি জায়গায় সাজাতে ব্যবহৃত হয় এবং সাজানো অ্যারেটি প্রদান করে। উদাহরণ ব্যবহার নীচে দেখা যায়,

```javascript
var months = ["Aug", "Sep", "Jan", "June"];
months.sort();
console.log(months); //  ["Aug", "Jan", "June", "Sep"]
```
243.  ### What is the purpose of compareFunction while sorting arrays

      The compareFunction is used to define the sort order. If omitted, the array elements are converted to strings, then sorted according to each character's Unicode code point value. Let's take an example to see the usage of compareFunction,

      ```javascript
      let numbers = [1, 2, 5, 3, 4];
      numbers.sort((a, b) => b - a);
      console.log(numbers); // [5, 4, 3, 2, 1]
      ```

      **[⬆ Back to Top](#table-of-contents)**
### অ্যারে সাজানোর সময় compareFunction এর উদ্দেশ্য কি

compareFunction টি ব্যবহার হয় সাজানোর ক্রম নির্ধারণ করার জন্য। যদি এটি অকার্যকর থাকে, তবে অ্যারের উপাদানগুলি স্ট্রিংয়ে রূপান্তরিত হয় এবং প্রতিটি অক্ষরের Unicode কোড পয়েন্ট মান অনুযায়ী সাজানো হয়। এটি ব্যবহারের উদাহরণ দেখতে একটি উদাহরণ নিন,

```javascript
let numbers = [1, 2, 5, 3, 4];
numbers.sort((a, b) => b - a);
console.log(numbers); // [5, 4, 3, 2, 1]
```
244.  ### How do you reversing an array

      You can use the reverse() method to reverse the elements in an array. This method is useful to sort an array in descending order. Let's see the usage of reverse() method in an example,

      ```javascript
      let numbers = [1, 2, 5, 3, 4];
      numbers.sort((a, b) => b - a);
      numbers.reverse();
      console.log(numbers); // [1, 2, 3, 4 ,5]
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কিভাবে একটি অ্যারে রিভার্স করবেন

আপনি একটি অ্যারেতে উপাদানগুলি রিভার্স করতে reverse() মেথডটি ব্যবহার করতে পারেন। এই মেথডটি অ্যারেটি ডিসেন্ডিং অর্ডারে সাজানোর জন্য দরকারি। এটির ব্যবহারটি একটি উদাহরণে দেখা যাক,

```javascript
let numbers = [1, 2, 5, 3, 4];
numbers.sort((a, b) => b - a);
numbers.reverse();
console.log(numbers); // [1, 2, 3, 4, 5]
```
245.  ### How do you find min and max value in an array

      You can use `Math.min` and `Math.max` methods on array variables to find the minimum and maximum elements within an array. Let's create two functions to find the min and max value with in an array,

      ```javascript
      var marks = [50, 20, 70, 60, 45, 30];
      function findMin(arr) {
        return Math.min.apply(null, arr);
      }
      function findMax(arr) {
        return Math.max.apply(null, arr);
      }

      console.log(findMin(marks));
      console.log(findMax(marks));
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কিভাবে একটি অ্যারেতে সর্বনিম্ন এবং সর্বাধিক মান খুঁজবেন

আপনি অ্যারের ভ্যারিয়েবলে Math.min এবং Math.max মেথডগুলি ব্যবহার করতে পারেন অ্যারেতে সর্বনিম্ন এবং সর্বাধিক উপাদান খুঁজতে। একটি অ্যারেতে সর্বনিম্ন এবং সর্বাধিক মান খুঁজতে দুটি ফাংশন তৈরি করা যাক,

```javascript
var marks = [50, 20, 70, 60, 45, 30];
function findMin(arr) {
  return Math.min.apply(null, arr);
}
function findMax(arr) {
  return Math.max.apply(null, arr);
}

console.log(findMin(marks));
console.log(findMax(marks));
```
246.  ### How do you find min and max values without Math functions

      You can write functions which loop through an array comparing each value with the lowest value or highest value to find the min and max values. Let's create those functions to find min and max values,

      ```javascript
      var marks = [50, 20, 70, 60, 45, 30];
      function findMin(arr) {
        var length = arr.length;
        var min = Infinity;
        while (length--) {
          if (arr[length] < min) {
            min = arr[length];
          }
        }
        return min;
      }

      function findMax(arr) {
        var length = arr.length;
        var max = -Infinity;
        while (length--) {
          if (arr[length] > max) {
            max = arr[length];
          }
        }
        return max;
      }

      console.log(findMin(marks));
      console.log(findMax(marks));
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কিভাবে Math ফাংশন ছাড়াই সর্বনিম্ন এবং সর্বাধিক মান খুঁজবেন

আপনি একটি ফাংশন লেখতে পারেন যা একটি অ্যারে দিয়ে লুপ চালিয়ে প্রতি মানকে সর্বনিম্ন মান বা সর্বাধিক মানের সাথে তুলনা করে এবং সর্বনিম্ন এবং সর্বাধিক মানগুলি খুঁজে বের করে। আসুন সেই ফাংশনগুলি তৈরি করি,

```javascript
var marks = [50, 20, 70, 60, 45, 30];

function findMin(arr) {
  var length = arr.length;
  var min = Infinity;
  while (length--) {
    if (arr[length] < min) {
      min = arr[length];
    }
  }
  return min;
}

function findMax(arr) {
  var length = arr.length;
  var max = -Infinity;
  while (length--) {
    if (arr[length] > max) {
      max = arr[length];
    }
  }
  return max;
}

console.log(findMin(marks));
console.log(findMax(marks));
```
247.  ### What is an empty statement and purpose of it

      The empty statement is a semicolon (;) indicating that no statement will be executed, even if JavaScript syntax requires one. Since there is no action with an empty statement you might think that it's usage is quite less, but the empty statement is occasionally useful when you want to create a loop that has an empty body. For example, you can initialize an array with zero values as below,

      ```javascript
      // Initialize an array a
      for (let i = 0; i < a.length; a[i++] = 0);
      ```

      **[⬆ Back to Top](#table-of-contents)**
### শূন্য স্টেটমেন্ট কি এবং এর উদ্দেশ্য

শূন্য স্টেটমেন্ট হলো একটি সেমিকোলন (;) যা প্রতিবাদ করে যে কোনও স্টেটমেন্ট সঞ্চালিত হবে না, যদি জাভাস্ক্রিপ্ট সিনট্যাক্স একটি স্টেটমেন্ট প্রয়োজন করে। শূন্য স্টেটমেন্টের সাথে কোনও কাজ নেই তাই আপনি যদি মনে করেন যে এটি ব্যবহার কম, তবে শূন্য স্টেটমেন্টটি কখনও ব্যবহারযোগ্য হয় যখন আপনি একটি শূন্য বডি সহ একটি লুপ তৈরি করতে চান। উদাহরণস্বরূপ, আপনি একটি অ্যারেকে শূন্য মান দিয়ে ইনিসিয়ালাইজ করতে পারেন,

```javascript
// একটি অ্যারে a ইনিসিয়ালাইজ করুন
for (let i = 0; i < a.length; a[i++] = 0);
```
248.  ### How do you get metadata of a module

      You can use the `import.meta` object which is a meta-property exposing context-specific meta data to a JavaScript module. It contains information about the current module, such as the module's URL. In browsers, you might get different meta data than NodeJS.

      ```javascript
      <script type="module" src="welcome-module.js"></script>;
      console.log(import.meta); // { url: "file:///home/user/welcome-module.js" }
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কিভাবে একটি মডিউলের মেটাডেটা পাওয়া যায়

আপনি `import.meta` অবজেক্ট ব্যবহার করতে পারেন, যা একটি জাভাস্ক্রিপ্ট মডিউলে সংদর্ভ-বিশিষ্ট মেটা ডেটা উপস্থাপন করে। এটি বর্তমান মডিউলের তথ্য সহ যেগুলি থাকে, সেগুলি যেমন মডিউলের URL ইত্যাদি। ব্রাউজারে, আপনি নোডজেএসের তুলনায় আলাদা মেটা ডেটা পাবেন।

```javascript
<script type="module" src="welcome-module.js"></script>;
console.log(import.meta); // { url: "file:///home/user/welcome-module.js" }
```
249.  ### What is a comma operator

      The comma operator is used to evaluate each of its operands from left to right and returns the value of the last operand. This is totally different from comma usage within arrays, objects, and function arguments and parameters. For example, the usage for numeric expressions would be as below,

      ```javascript
      var x = 1;
      x = (x++, x);

      console.log(x); // 2
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কমা অপারেটর

কমা অপারেটরটি তার অপারেন্ডগুলি বাম থেকে ডানে মূল্যায়ন করতে এবং শেষ অপারেন্ডের মানটি প্রদান করতে ব্যবহৃত হয়। এটি সম্পূর্ণভাবে অ্যারে, অবজেক্ট, এবং ফাংশনের আরওয়াম প্যারামিটার এবং আরগুমেন্টগুলির মধ্যে কমা ব্যবহারের থেকে সংকোচ করা। উদাহরণস্বরূপ, এর মান গণনার জন্য সংখ্যার অভিব্যন্তি হতে পারে এমন -

```javascript
var x = 1;
x = (x++, x);

console.log(x); // 2
```
250.  ### What is the advantage of a comma operator

      It is normally used to include multiple expressions in a location that requires a single expression. One of the common usages of this comma operator is to supply multiple parameters in a `for` loop. For example, the below for loop uses multiple expressions in a single location using comma operator,

      ```javascript
      for (var a = 0, b =10; a <= 10; a++, b--)
      ```

      You can also use the comma operator in a return statement where it processes before returning.

      ```javascript
      function myFunction() {
        var a = 1;
        return (a += 10), a; // 11
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কমা অপারেটরের সুবিধা

সাধারণভাবে এটি একটি সিঙ্গল এক্সপ্রেশন প্রয়োজন স্থানে একাধিক এক্সপ্রেশন অন্তর্ভুক্ত করার জন্য ব্যবহৃত হয়। এই কমা অপারেটরের একটি সাধারিত ব্যবহার হল একটি `for` লুপে একাধিক প্যারামিটার সরবরাহ করা। উদাহরণস্বরূপ, নিচের ফর লুপটি একাধিক এক্সপ্রেশন ব্যবহার করে একটি সিঙ্গল স্থানে -

```javascript
for (var a = 0, b = 10; a <= 10; a++, b--)
```
আপনি রিটার্ন স্টেটমেন্টেও কমা অপারেটর ব্যবহার করতে পারেন যেখানে এটি রিটার্ন হওয়ার আগে প্রসেস হয়।
```javascript
function myFunction() {
  var a = 1;
  return (a += 10), a; // 11
}

```
251.  ### What is typescript

      TypeScript is a typed superset of JavaScript created by Microsoft that adds optional types, classes, async/await, and many other features, and compiles to plain JavaScript. Angular built entirely in TypeScript and used as a primary language. You can install it globally as

      ```bash
      npm install -g typescript
      ```

      Let's see a simple example of TypeScript usage,

      ```typescript
      function greeting(name: string): string {
        return "Hello, " + name;
      }

      let user = "Sudheer";

      console.log(greeting(user));
      ```

      The greeting method allows only string type as argument.

      **[⬆ Back to Top](#table-of-contents)**
### টাইপস্ক্রিপ্ট

টাইপস্ক্রিপ্ট হলো জাভাস্ক্রিপ্টের একটি টাইপড সাপারসেট, যা মাইক্রোসফট তৈরি করেছে এবং এটি অপশনাল টাইপ, ক্লাস, এসিঙ্ক/অয়েট, এবং অনেক অন্যান্য ফিচার যোগ করে, এবং এটি সাধারিত জাভাস্ক্রিপ্টে কম্পাইল হয়। অ্যাঙ্গুলারও পূর্নাঙ্গ টাইপস্ক্রিপ্টে তৈরি এবং এটির প্রাথমিক ভাষা হিসেবে ব্যবহৃত হয়। আপনি এটি গ্লোবালি ইনস্টল করতে পারেন

```bash
npm install -g typescript
```
চলুন টাইপস্ক্রিপ্ট ব্যবহারের একটি সাধারিত উদাহরণ দেখি,
```javascript
function greeting(name: string): string {
  return "Hello, " + name;
}

let user = "Sudheer";

console.log(greeting(user));
```
এই গ্রিটিং মেথডটি শুধুমাত্র স্ট্রিং টাইপকে আর্গুমেন্ট হিসেবে অনুমোদন করে।

252.  ### What are the differences between javascript and typescript

      Below are the list of differences between javascript and typescript,

      | feature             | typescript                            | javascript                                      |
      | ------------------- | ------------------------------------- | ----------------------------------------------- |
      | Language paradigm   | Object oriented programming language  | Scripting language                              |
      | Typing support      | Supports static typing                | It has dynamic typing                           |
      | Modules             | Supported                             | Not supported                                   |
      | Interface           | It has interfaces concept             | Doesn't support interfaces                      |
      | Optional parameters | Functions support optional parameters | No support of optional parameters for functions |

      **[⬆ Back to Top](#table-of-contents)**
### জাভাস্ক্রিপ্ট এবং টাইপস্ক্রিপ্টের পার্থক্য

নীচে জাভাস্ক্রিপ্ট এবং টাইপস্ক্রিপ্ট মধ্যে বিভিন্ন পার্থক্যের তালিকা দেওয়া হয়েছে,

| বৈশিষ্ট্য              | টাইপস্ক্রিপ্ট                          | জাভাস্ক্রিপ্ট                                  |
| ------------------- | ------------------------------------- | ----------------------------------------------- |
| ভাষা প্যারাডাইম   | অবজেক্ট ওয়ারিএন্টেড প্রোগ্রামিং ভাষা  | স্ক্রিপ্টিং ভাষা                              |
| টাইপিং সাপোর্ট     | স্ট্যাটিক টাইপিং সাপোর্ট করে            | এটি ডাইনামিক টাইপিং সাপোর্ট করে              |
| মডিউল              | সাপোর্ট করে                           | সাপোর্ট করেনা                                  |
| ইন্টারফেস           | ইন্টারফেস ধারণা সাপোর্ট করে            | ইন্টারফেস সাপোর্ট করেনা                       |
| অপশনাল প্যারামিটার | ফাংশনগুলিতে অপশনাল প্যারামিটার সাপোর্ট করে | ফাংশনের জন্য অপশনাল প্যারামিটারের সাপোর্ট নেই |

**[⬆ উপরে ফিরে যান](#table-of-contents)**

253.  ### What are the advantages of typescript over javascript

      Below are some of the advantages of typescript over javascript,

      1.  TypeScript is able to find compile time errors at the development time only and it makes sures less runtime errors. Whereas javascript is an interpreted language.
      2.  TypeScript is strongly-typed or supports static typing which allows for checking type correctness at compile time. This is not available in javascript.
      3.  TypeScript compiler can compile the .ts files into ES3,ES4 and ES5 unlike ES6 features of javascript which may not be supported in some browsers.

      **[⬆ Back to Top](#table-of-contents)**
### জাভাস্ক্রিপ্টের উপর টাইপস্ক্রিপ্টের উপকারিতা

নীচে জাভাস্ক্রিপ্টের উপর টাইপস্ক্রিপ্টের কিছু উপকারিতা দেওয়া হয়েছে,

1.  টাইপস্ক্রিপ্ট প্রারম্ভিক সময়েই কম্পাইল টাইম ত্রুটি খুজে বের করতে পারে এবং এটি সিদ্ধান্ত নেয় যে কোনো রানটাইম ত্রুটির সংখ্যা কম থাকবে। যেহেতু জাভাস্ক্রিপ্ট একটি ইন্টারপ্রেটেড ভাষা.
2.  টাইপস্ক্রিপ্ট স্ট্রংলি-টাইপড বা স্ট্যাটিক টাইপিং সাপোর্ট করে যা কম্পাইল সময়ে টাইপ সঠিকতা পরীক্ষা করার অনুমতি দেয়। এটি জাভাস্ক্রিপ্টে উপলব্ধ নয়।
3.  টাইপস্ক্রিপ্ট কম্পাইলার এটি .ts ফাইলগুলি কম্পাইল করতে পারে ES3, ES4 এবং ES5 এ, যা জাভাস্ক্রিপ্টে অনুমোদিত নয় হতে পারে কিন্তু ES6 ফিচারগুলি।

**[⬆ উপরে ফিরে যান](#table-of-contents)**

254.  ### What is an object initializer

      An object initializer is an expression that describes the initialization of an Object. The syntax for this expression is represented as a comma-delimited list of zero or more pairs of property names and associated values of an object, enclosed in curly braces ({}). This is also known as literal notation. It is one of the ways to create an object.

      ```javascript
      var initObject = { a: "John", b: 50, c: {} };

      console.log(initObject.a); // John
      ```

      **[⬆ Back to Top](#table-of-contents)**
### অবজেক্ট ইনিশিয়ালাইজার

অবজেক্ট ইনিশিয়ালাইজার হলো একটি অবজেক্টের ইনিশিয়ালাইজেশন বর্ণনা করার একটি অভ্যন্তরীণ। এই এক্সপ্রেশনের সিনট্যাক্সটি একটি অবজেক্টের সংজ্ঞার একটি অংশ হিসেবে প্রদর্শিত হয়, যা কোমা দ্বারা পৃথক করা হয় শূন্য বা একাধিক অবজেক্ট বৈশিষ্ট্য এবং সাথে সম্পর্কিত মান, কুড়লি বন্ধনীতে মোচনকৃত, ব্যক্ত করা হয় ({} এর মধ্যে)। এটি লিটারেল নোটেশন হিসেবেও পরিচিত। এটি একটি অবজেক্ট তৈরি করার একটি উপায়।

```javascript
var initObject = { a: "John", b: 50, c: {} };

console.log(initObject.a); // John
```
255.  ### What is a constructor method

      The constructor method is a special method for creating and initializing an object created within a class. If you do not specify a constructor method, a default constructor is used. The example usage of constructor would be as below,

      ```javascript
      class Employee {
        constructor() {
          this.name = "John";
        }
      }

      var employeeObject = new Employee();

      console.log(employeeObject.name); // John
      ```

      **[⬆ Back to Top](#table-of-contents)**
### কনস্ট্রাক্টর মেথড

কনস্ট্রাক্টর মেথডটি হলো একটি বিশেষ মেথড যা একটি ক্লাসের মধ্যে তৈরি এবং একটি অবজেক্ট তৈরি এবং তার শুরুতে ইনিশিয়ালাইজ করতে ব্যবহৃত হয়। আপনি যদি একটি কনস্ট্রাক্টর মেথড সুনির্দিষ্ট করেন না, তবে একটি ডিফল্ট কনস্ট্রাক্টর ব্যবহৃত হয়। কনস্ট্রাক্টরের একটি উদাহরণ হতে পারে নিচের মত,

```javascript
class Employee {
  constructor() {
    this.name = "John";
  }
}

var employeeObject = new Employee();

console.log(employeeObject.name); // John
```
256.  ### What happens if you write constructor more than once in a class

      The "constructor" in a class is a special method and it should be defined only once in a class. i.e, If you write a constructor method more than once in a class it will throw a `SyntaxError` error.

      ```javascript
       class Employee {
         constructor() {
           this.name = "John";
         }
         constructor() {   //  Uncaught SyntaxError: A class may only have one constructor
           this.age = 30;
         }
       }

       var employeeObject = new Employee();

       console.log(employeeObject.name);
      ```

      **[⬆ Back to Top](#table-of-contents)**
### ক্লাসে কনস্ট্রাক্টর একাধিকবার লেখা হলে কি হয়

ক্লাসে "কনস্ট্রাক্টর" হলো একটি বিশেষ মেথড এবং এটি ক্লাসে একবার মাত্র লেখা হয়। অর্থাৎ, আপনি যদি একটি ক্লাসে একাধিকবার কনস্ট্রাক্টর মেথড লেখেন তাও এটি একটি `SyntaxError` তৈরি করবে।

```javascript
class Employee {
  constructor() {
    this.name = "John";
  }
  constructor() {   //  Uncaught SyntaxError: A class may only have one constructor
    this.age = 30;
  }
}

var employeeObject = new Employee();

console.log(employeeObject.name);
```
257.  ### How do you call the constructor of a parent class

      You can use the `super` keyword to call the constructor of a parent class. Remember that `super()` must be called before using 'this' reference. Otherwise it will cause a reference error. Let's the usage of it,

      ```javascript
      class Square extends Rectangle {
        constructor(length) {
          super(length, length);
          this.name = "Square";
        }

        get area() {
          return this.width * this.height;
        }

        set area(value) {
          this.area = value;
        }
      }
      ```
      **[⬆ Back to Top](#table-of-contents)**
### কিভাবে একটি প্যারেন্ট ক্লাসের কনস্ট্রাক্টর কল করতে হয়

আপনি প্যারেন্ট ক্লাসের কনস্ট্রাক্টর কল করতে `super` কীওয়ার্ড ব্যবহার করতে পারেন। মনে রাখবেন যে, `super()` কল করা আবশ্যক এবং এটি 'this' রেফারেন্স ব্যবহার করার আগে কল করা আবশ্যক। অথবা এটি রেফারেন্স এরর তৈরি করবে। এর ব্যবহার একটি উদাহরণে দেখানো হয়েছে,

```javascript
class Square extends Rectangle {
  constructor(length) {
    super(length, length);
    this.name = "Square";
  }

  get area() {
    return this.width * this.height;
  }

  set area(value) {
    this.area = value;
  }
}
```
258.  ### How do you get the prototype of an object

      You can use the `Object.getPrototypeOf(obj)` method to return the prototype of the specified object. i.e. The value of the internal `prototype` property. If there are no inherited properties then `null` value is returned.

      ```javascript
      const newPrototype = {};
      const newObject = Object.create(newPrototype);

      console.log(Object.getPrototypeOf(newObject) === newPrototype); // true
      ```

      **[⬆ Back to Top](#table-of-contents)**

### একটি অবজেক্টের প্রোটোটাইপ কিভাবে পেতে হয়

আপনি `Object.getPrototypeOf(obj)` মেথড ব্যবহার করতে পারেন যেটি নির্দিষ্ট অবজেক্টের প্রোটোটাইপ কে ফিরিয়ে দেয়। অর্থাৎ, অভ্যন্তরীণ `prototype` প্রপার্টির মান। যদি কোনও ইনহেরিটেড প্রোপার্টি না থাকে তাদের জন্য `null` মান প্রদান করা হয়।

```javascript
const newPrototype = {};
const newObject = Object.create(newPrototype);

console.log(Object.getPrototypeOf(newObject) === newPrototype); // true
```
259.  ### What happens If I pass string type for getPrototype method

      In ES5, it will throw a TypeError exception if the obj parameter isn't an object. Whereas in ES2015, the parameter will be coerced to an `Object`.

      ```javascript
      // ES5
      Object.getPrototypeOf("James"); // TypeError: "James" is not an object
      // ES2015
      Object.getPrototypeOf("James"); // String.prototype
      ```

      **[⬆ Back to Top](#table-of-contents)**
### আমি getPrototype মেথডে স্ট্রিং টাইপ পাস করলে কি হয়

ES5 এ, যদি obj প্যারামিটারটি একটি অবজেক্ট না হয় তবে এটি একটি TypeError একসেপশন ফেলবে। অপরদিকে, ES2015 এ, প্যারামিটারটি একটি `Object` হিসেবে প্রোটাইপ করা হবে।

```javascript
// ES5
Object.getPrototypeOf("James"); // TypeError: "James" is not an object
// ES2015
Object.getPrototypeOf("James"); // String.prototype
```
260.  ### How do you set prototype of one object to another

      You can use the `Object.setPrototypeOf()` method that sets the prototype (i.e., the internal `Prototype` property) of a specified object to another object or null. For example, if you want to set prototype of a square object to rectangle object would be as follows,

      ```javascript
      Object.setPrototypeOf(Square.prototype, Rectangle.prototype);
      Object.setPrototypeOf({}, null);
      ```

      **[⬆ Back to Top](#table-of-contents)**
### একটি অবজেক্টের প্রোটোটাইপকে অপর অবজেক্টে কীভাবে সেট করা যায়

আপনি `Object.setPrototypeOf()` মেথডটি ব্যবহার করতে পারেন, যা নির্দিষ্ট একটি অবজেক্টের প্রোটোটাইপকে (অর্থাৎ, আভ্যন্তরিক `Prototype` প্রপার্টি) অপর একটি অবজেক্ট বা নাল এ সেট করে। উদাহরণস্বরূপ, একটি বর্গের অবজেক্টের প্রোটোটাইপকে আরেকটি রেক্ট্যাঙ্গল অবজেক্টে সেট করতে চান তার উদাহরণ হবে,

```javascript
Object.setPrototypeOf(Square.prototype, Rectangle.prototype);
Object.setPrototypeOf({}, null);
```
261.  ### How do you check whether an object can be extendable or not

      The `Object.isExtensible()` method is used to determine if an object is extendable or not. i.e, Whether it can have new properties added to it or not.

      ```javascript
      const newObject = {};
      console.log(Object.isExtensible(newObject)); //true
      ```

      **Note:** By default, all the objects are extendable. i.e, The new properties can be added or modified.

      **[⬆ Back to Top](#table-of-contents)**

262.  ### How do you prevent an object to extend

      The `Object.preventExtensions()` method is used to prevent new properties from ever being added to an object. In other words, it prevents future extensions to the object. Let's see the usage of this property,

      ```javascript
      const newObject = {};
      Object.preventExtensions(newObject); // NOT extendable

      try {
        Object.defineProperty(newObject, "newProperty", {
          // Adding new property
          value: 100,
        });
      } catch (e) {
        console.log(e); // TypeError: Cannot define property newProperty, object is not extensible
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

263.  ### What are the different ways to make an object non-extensible

      You can mark an object non-extensible in 3 ways,

      1.  Object.preventExtensions
      2.  Object.seal
      3.  Object.freeze

      ```javascript
      var newObject = {};

      Object.preventExtensions(newObject); // Prevent objects are non-extensible
      Object.isExtensible(newObject); // false

      var sealedObject = Object.seal({}); // Sealed objects are non-extensible
      Object.isExtensible(sealedObject); // false

      var frozenObject = Object.freeze({}); // Frozen objects are non-extensible
      Object.isExtensible(frozenObject); // false
      ```

      **[⬆ Back to Top](#table-of-contents)**

264.  ### How do you define multiple properties on an object

      The `Object.defineProperties()` method is used to define new or modify existing properties directly on an object and returning the object. Let's define multiple properties on an empty object,

      ```javascript
      const newObject = {};

      Object.defineProperties(newObject, {
        newProperty1: {
          value: "John",
          writable: true,
        },
        newProperty2: {},
      });
      ```

      **[⬆ Back to Top](#table-of-contents)**

265.  ### What is MEAN in javascript

      The MEAN (MongoDB, Express, AngularJS, and Node.js) stack is the most popular open-source JavaScript software tech stack available for building dynamic web apps where you can write both the server-side and client-side halves of the web project entirely in JavaScript.

      **[⬆ Back to Top](#table-of-contents)**

266.  ### What Is Obfuscation in javascript

      Obfuscation is the deliberate act of creating obfuscated javascript code(i.e, source or machine code) that is difficult for humans to understand. It is something similar to encryption, but a machine can understand the code and execute it.
      Let's see the below function before Obfuscation,

      ```javascript
      function greeting() {
        console.log("Hello, welcome to JS world");
      }
      ```

      And after the code Obfuscation, it would be appeared as below,

      ```javascript
      eval(
        (function (p, a, c, k, e, d) {
          e = function (c) {
            return c;
          };
          if (!"".replace(/^/, String)) {
            while (c--) {
              d[c] = k[c] || c;
            }
            k = [
              function (e) {
                return d[e];
              },
            ];
            e = function () {
              return "\\w+";
            };
            c = 1;
          }
          while (c--) {
            if (k[c]) {
              p = p.replace(new RegExp("\\b" + e(c) + "\\b", "g"), k[c]);
            }
          }
          return p;
        })(
          "2 1(){0.3('4, 7 6 5 8')}",
          9,
          9,
          "console|greeting|function|log|Hello|JS|to|welcome|world".split("|"),
          0,
          {}
        )
      );
      ```

      **[⬆ Back to Top](#table-of-contents)**

267.  ### Why do you need Obfuscation

      Below are the few reasons for Obfuscation,

      1.  The Code size will be reduced. So data transfers between server and client will be fast.
      2.  It hides the business logic from outside world and protects the code from others
      3.  Reverse engineering is highly difficult
      4.  The download time will be reduced

      **[⬆ Back to Top](#table-of-contents)**

268.  ### What is Minification

      Minification is the process of removing all unnecessary characters(empty spaces are removed) and variables will be renamed without changing it's functionality. It is also a type of obfuscation .

      **[⬆ Back to Top](#table-of-contents)**

269.  ### What are the advantages of minification

      Normally it is recommended to use minification for heavy traffic and intensive requirements of resources. It reduces file sizes with below benefits,

      1.  Decreases loading times of a web page
      2.  Saves bandwidth usages

      **[⬆ Back to Top](#table-of-contents)**

270.  ### What are the differences between Obfuscation and Encryption

      Below are the main differences between Obfuscation and Encryption,

      | Feature            | Obfuscation                                     | Encryption                                                              |
      | ------------------ | ----------------------------------------------- | ----------------------------------------------------------------------- |
      | Definition         | Changing the form of any data in any other form | Changing the form of information to an unreadable format by using a key |
      | A key to decode    | It can be decoded without any key               | It is required                                                          |
      | Target data format | It will be converted to a complex form          | Converted into an unreadable format                                     |

      **[⬆ Back to Top](#table-of-contents)**

271.  ### What are the common tools used for minification

      There are many online/offline tools to minify the javascript files,

      1.  Google's Closure Compiler
      2.  UglifyJS2
      3.  jsmin
      4.  javascript-minifier.com/
      5.  prettydiff.com

      **[⬆ Back to Top](#table-of-contents)**

272.  ### How do you perform form validation using javascript

      JavaScript can be used to perform HTML form validation. For example, if the form field is empty, the function needs to notify, and return false, to prevent the form being submitted.
      Lets' perform user login in an html form,

      ```html
      <form name="myForm" onsubmit="return validateForm()" method="post">
        User name: <input type="text" name="uname" />
        <input type="submit" value="Submit" />
      </form>
      ```

      And the validation on user login is below,

      ```javascript
      function validateForm() {
        var x = document.forms["myForm"]["uname"].value;
        if (x == "") {
          alert("The username shouldn't be empty");
          return false;
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

273.  ### How do you perform form validation without javascript

      You can perform HTML form validation automatically without using javascript. The validation enabled by applying the `required` attribute to prevent form submission when the input is empty.

      ```html
      <form method="post">
        <input type="text" name="uname" required />
        <input type="submit" value="Submit" />
      </form>
      ```

      **Note:** Automatic form validation does not work in Internet Explorer 9 or earlier.

      **[⬆ Back to Top](#table-of-contents)**

274.  ### What are the DOM methods available for constraint validation

      The below DOM methods are available for constraint validation on an invalid input,

      1.  checkValidity(): It returns true if an input element contains valid data.
      2.  setCustomValidity(): It is used to set the validationMessage property of an input element.
          Let's take an user login form with DOM validations

      ```javascript
      function myFunction() {
        var userName = document.getElementById("uname");
        if (!userName.checkValidity()) {
          document.getElementById("message").innerHTML =
            userName.validationMessage;
        } else {
          document.getElementById("message").innerHTML =
            "Entered a valid username";
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

275.  ### What are the available constraint validation DOM properties

      Below are the list of some of the constraint validation DOM properties available,

      1.  validity: It provides a list of boolean properties related to the validity of an input element.
      2.  validationMessage: It displays the message when the validity is false.
      3.  willValidate: It indicates if an input element will be validated or not.

      **[⬆ Back to Top](#table-of-contents)**

276.  ### What are the list of validity properties

      The validity property of an input element provides a set of properties related to the validity of data.

      1.  customError: It returns true, if a custom validity message is set.
      2.  patternMismatch: It returns true, if an element's value does not match its pattern attribute.
      3.  rangeOverflow: It returns true, if an element's value is greater than its max attribute.
      4.  rangeUnderflow: It returns true, if an element's value is less than its min attribute.
      5.  stepMismatch: It returns true, if an element's value is invalid according to step attribute.
      6.  tooLong: It returns true, if an element's value exceeds its maxLength attribute.
      7.  typeMismatch: It returns true, if an element's value is invalid according to type attribute.
      8.  valueMissing: It returns true, if an element with a required attribute has no value.
      9.  valid: It returns true, if an element's value is valid.

      **[⬆ Back to Top](#table-of-contents)**

277.  ### Give an example usage of rangeOverflow property

      If an element's value is greater than its max attribute then rangeOverflow property returns true. For example, the below form submission throws an error if the value is more than 100,

      ```html
      <input id="age" type="number" max="100" />
      <button onclick="myOverflowFunction()">OK</button>
      ```

      ```javascript
      function myOverflowFunction() {
        if (document.getElementById("age").validity.rangeOverflow) {
          alert("The mentioned age is not allowed");
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

278.  ### Is enums feature available in javascript

      No, javascript does not natively support enums. But there are different kinds of solutions to simulate them even though they may not provide exact equivalents. For example, you can use freeze or seal on object,

      ```javascript
      var DaysEnum = Object.freeze({"monday":1, "tuesday":2, "wednesday":3, ...})
      ```

      **[⬆ Back to Top](#table-of-contents)**

279.  ### What is an enum

      An enum is a type restricting variables to one value from a predefined set of constants. JavaScript has no enums but typescript provides built-in enum support.

      ```javascript
      enum Color {
       RED, GREEN, BLUE
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

280.  ### How do you list all properties of an object

      You can use the `Object.getOwnPropertyNames()` method which returns an array of all properties found directly in a given object. Let's the usage of it in an example,

      ```javascript
      const newObject = {
        a: 1,
        b: 2,
        c: 3,
      };

      console.log(Object.getOwnPropertyNames(newObject));
      ["a", "b", "c"];
      ```

      **[⬆ Back to Top](#table-of-contents)**

281.  ### How do you get property descriptors of an object

      You can use the `Object.getOwnPropertyDescriptors()` method which returns all own property descriptors of a given object. The example usage of this method is below,

      ```javascript
      const newObject = {
        a: 1,
        b: 2,
        c: 3,
      };
      const descriptorsObject = Object.getOwnPropertyDescriptors(newObject);
      console.log(descriptorsObject.a.writable); //true
      console.log(descriptorsObject.a.configurable); //true
      console.log(descriptorsObject.a.enumerable); //true
      console.log(descriptorsObject.a.value); // 1
      ```

      **[⬆ Back to Top](#table-of-contents)**

282.  ### What are the attributes provided by a property descriptor

      A property descriptor is a record which has the following attributes

      1.  value: The value associated with the property
      2.  writable: Determines whether the value associated with the property can be changed or not
      3.  configurable: Returns true if the type of this property descriptor can be changed and if the property can be deleted from the corresponding object.
      4.  enumerable: Determines whether the property appears during enumeration of the properties on the corresponding object or not.
      5.  set: A function which serves as a setter for the property
      6.  get: A function which serves as a getter for the property

      **[⬆ Back to Top](#table-of-contents)**

283.  ### How do you extend classes

      The `extends` keyword is used in class declarations/expressions to create a class which is a child of another class. It can be used to subclass custom classes as well as built-in objects. The syntax would be as below,

      ```javascript
      class ChildClass extends ParentClass { ... }
      ```

      Let's take an example of Square subclass from Polygon parent class,

      ```javascript
      class Square extends Rectangle {
        constructor(length) {
          super(length, length);
          this.name = "Square";
        }

        get area() {
          return this.width * this.height;
        }

        set area(value) {
          this.area = value;
        }
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

284.  ### How do I modify the url without reloading the page

      The `window.location.href` property will be helpful to modify the url but it reloads the page. HTML5 introduced the `history.pushState()` and `history.replaceState()` methods, which allow you to add and modify history entries, respectively. For example, you can use pushState as below,

      ```javascript
      window.history.pushState("page2", "Title", "/page2.html");
      ```

      **[⬆ Back to Top](#table-of-contents)**

285.  ### How do you check whether an array includes a particular value or not

      The `Array#includes()` method is used to determine whether an array includes a particular value among its entries by returning either true or false. Let's see an example to find an element(numeric and string) within an array.

      ```javascript
      var numericArray = [1, 2, 3, 4];
      console.log(numericArray.includes(3)); // true

      var stringArray = ["green", "yellow", "blue"];
      console.log(stringArray.includes("blue")); //true
      ```

      **[⬆ Back to Top](#table-of-contents)**

286.  ### How do you compare scalar arrays

      You can use length and every method of arrays to compare two scalar(compared directly using ===) arrays. The combination of these expressions can give the expected result,

      ```javascript
      const arrayFirst = [1, 2, 3, 4, 5];
      const arraySecond = [1, 2, 3, 4, 5];
      console.log(
        arrayFirst.length === arraySecond.length &&
          arrayFirst.every((value, index) => value === arraySecond[index])
      ); // true
      ```

      If you would like to compare arrays irrespective of order then you should sort them before,

      ```javascript
      const arrayFirst = [2, 3, 1, 4, 5];
      const arraySecond = [1, 2, 3, 4, 5];
      console.log(
        arrayFirst.length === arraySecond.length &&
          arrayFirst
            .sort()
            .every((value, index) => value === arraySecond[index])
      ); //true
      ```

      **[⬆ Back to Top](#table-of-contents)**

287.  ### How to get the value from get parameters

      The `new URL()` object accepts the url string and `searchParams` property of this object can be used to access the get parameters. Remember that you may need to use polyfill or `window.location` to access the URL in older browsers(including IE).

      ```javascript
      let urlString = "http://www.some-domain.com/about.html?x=1&y=2&z=3"; //window.location.href
      let url = new URL(urlString);
      let parameterZ = url.searchParams.get("z");
      console.log(parameterZ); // 3
      ```

      **[⬆ Back to Top](#table-of-contents)**

288.  ### How do you print numbers with commas as thousand separators

      You can use the `Number.prototype.toLocaleString()` method which returns a string with a language-sensitive representation such as thousand separator,currency etc of this number.

      ```javascript
      function convertToThousandFormat(x) {
        return x.toLocaleString(); // 12,345.679
      }

      console.log(convertToThousandFormat(12345.6789));
      ```

      **[⬆ Back to Top](#table-of-contents)**

289.  ### What is the difference between java and javascript

      Both are totally unrelated programming languages and no relation between them. Java is statically typed, compiled, runs on its own VM. Whereas Javascript is dynamically typed, interpreted, and runs in a browser and nodejs environments. Let's see the major differences in a tabular format,
      | Feature | Java | JavaScript |
      |---- | ---- | -----
      | Typed | It's a strongly typed language | It's a dynamic typed language |
      | Paradigm | Object oriented programming | Prototype based programming |
      | Scoping | Block scoped | Function-scoped |
      | Concurrency | Thread based | event based |
      | Memory | Uses more memory | Uses less memory. Hence it will be used for web pages |

      **[⬆ Back to Top](#table-of-contents)**

290.  ### Does JavaScript supports namespace

      JavaScript doesn’t support namespace by default. So if you create any element(function, method, object, variable) then it becomes global and pollutes the global namespace. Let's take an example of defining two functions without any namespace,

      ```javascript
      function func1() {
        console.log("This is a first definition");
      }
      function func1() {
        console.log("This is a second definition");
      }
      func1(); // This is a second definition
      ```

      It always calls the second function definition. In this case, namespace will solve the name collision problem.

      **[⬆ Back to Top](#table-of-contents)**

291.  ### How do you declare namespace

      Even though JavaScript lacks namespaces, we can use Objects , IIFE to create namespaces.

      1.  **Using Object Literal Notation:** Let's wrap variables and functions inside an Object literal which acts as a namespace. After that you can access them using object notation

      ```javascript
      var namespaceOne = {
         function func1() {
             console.log("This is a first definition");
         }
      }
      var namespaceTwo = {
           function func1() {
               console.log("This is a second definition");
           }
       }
      namespaceOne.func1(); // This is a first definition
      namespaceTwo.func1(); // This is a second definition
      ```

      1.  **Using IIFE (Immediately invoked function expression):** The outer pair of parentheses of IIFE creates a local scope for all the code inside of it and makes the anonymous function a function expression. Due to that, you can create the same function in two different function expressions to act as a namespace.

      ```javascript
      (function () {
        function fun1() {
          console.log("This is a first definition");
        }
        fun1();
      })();

      (function () {
        function fun1() {
          console.log("This is a second definition");
        }
        fun1();
      })();
      ```

      1.  **Using a block and a let/const declaration:** In ECMAScript 6, you can simply use a block and a let declaration to restrict the scope of a variable to a block.

      ```javascript
      {
        let myFunction = function fun1() {
          console.log("This is a first definition");
        };
        myFunction();
      }
      //myFunction(): ReferenceError: myFunction is not defined.

      {
        let myFunction = function fun1() {
          console.log("This is a second definition");
        };
        myFunction();
      }
      //myFunction(): ReferenceError: myFunction is not defined.
      ```

      **[⬆ Back to Top](#table-of-contents)**

292.  ### How do you invoke javascript code in an iframe from parent page

      Initially iFrame needs to be accessed using either `document.getElementBy` or `window.frames`. After that `contentWindow` property of iFrame gives the access for targetFunction

      ```javascript
      document.getElementById("targetFrame").contentWindow.targetFunction();
      window.frames[0].frameElement.contentWindow.targetFunction(); // Accessing iframe this way may not work in latest versions chrome and firefox
      ```

      **[⬆ Back to Top](#table-of-contents)**

293.  ### How do get the timezone offset from date

      You can use the `getTimezoneOffset` method of the date object. This method returns the time zone difference, in minutes, from current locale (host system settings) to UTC

      ```javascript
      var offset = new Date().getTimezoneOffset();
      console.log(offset); // -480
      ```

      **[⬆ Back to Top](#table-of-contents)**

294.  ### How do you load CSS and JS files dynamically

      You can create both link and script elements in the DOM and append them as child to head tag. Let's create a function to add script and style resources as below,

      ```javascript
      function loadAssets(filename, filetype) {
        if (filetype == "css") {
          // External CSS file
          var fileReference = document.createElement("link");
          fileReference.setAttribute("rel", "stylesheet");
          fileReference.setAttribute("type", "text/css");
          fileReference.setAttribute("href", filename);
        } else if (filetype == "js") {
          // External JavaScript file
          var fileReference = document.createElement("script");
          fileReference.setAttribute("type", "text/javascript");
          fileReference.setAttribute("src", filename);
        }
        if (typeof fileReference != "undefined")
          document.getElementsByTagName("head")[0].appendChild(fileReference);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

295.  ### What are the different methods to find HTML elements in DOM

      If you want to access any element in an HTML page, you need to start with accessing the document object. Later you can use any of the below methods to find the HTML element,

      1.  document.getElementById(id): It finds an element by Id
      2.  document.getElementsByTagName(name): It finds an element by tag name
      3.  document.getElementsByClassName(name): It finds an element by class name

      **[⬆ Back to Top](#table-of-contents)**

296.  ### What is jQuery

      jQuery is a popular cross-browser JavaScript library that provides Document Object Model (DOM) traversal, event handling, animations and AJAX interactions by minimizing the discrepancies across browsers. It is widely famous with its philosophy of “Write less, do more”. For example, you can display welcome message on the page load using jQuery as below,

      ```javascript
      $(document).ready(function () {
        // It selects the document and apply the function on page load
        alert("Welcome to jQuery world");
      });
      ```

      **Note:** You can download it from jquery's official site or install it from CDNs, like google.

      **[⬆ Back to Top](#table-of-contents)**

297.  ### What is V8 JavaScript engine

      V8 is an open source high-performance JavaScript engine used by the Google Chrome browser, written in C++. It is also being used in the node.js project. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors.
      **Note:** It can run standalone, or can be embedded into any C++ application.

      **[⬆ Back to Top](#table-of-contents)**

298.  ### Why do we call javascript as dynamic language

      JavaScript is a loosely typed or a dynamic language because variables in JavaScript are not directly associated with any particular value type, and any variable can be assigned/reassigned with values of all types.

      ```javascript
      let age = 50; // age is a number now
      age = "old"; // age is a string now
      age = true; // age is a boolean
      ```

      **[⬆ Back to Top](#table-of-contents)**

299.  ### What is a void operator

      The `void` operator evaluates the given expression and then returns undefined(i.e, without returning value). The syntax would be as below,

      ```javascript
      void expression;
      void expression;
      ```

      Let's display a message without any redirection or reload

      ```javascript
      <a href="javascript:void(alert('Welcome to JS world'))">
        Click here to see a message
      </a>
      ```

      **Note:** This operator is often used to obtain the undefined primitive value, using "void(0)".

      **[⬆ Back to Top](#table-of-contents)**

300.  ### How to set the cursor to wait

      The cursor can be set to wait in JavaScript by using the property "cursor". Let's perform this behavior on page load using the below function.

      ```javascript
      function myFunction() {
        window.document.body.style.cursor = "wait";
      }
      ```

      and this function invoked on page load

      ```html
      <body onload="myFunction()"></body>
      ```

      **[⬆ Back to Top](#table-of-contents)**

301.  ### How do you create an infinite loop

      You can create infinite loops using for and while loops without using any expressions. The for loop construct or syntax is better approach in terms of ESLint and code optimizer tools,

      ```javascript
      for (;;) {}
      while (true) {}
      ```

      **[⬆ Back to Top](#table-of-contents)**

302.  ### Why do you need to avoid with statement

      JavaScript's with statement was intended to provide a shorthand for writing recurring accesses to objects. So it can help reduce file size by reducing the need to repeat a lengthy object reference without performance penalty. Let's take an example where it is used to avoid redundancy when accessing an object several times.

      ```javascript
      a.b.c.greeting = "welcome";
      a.b.c.age = 32;
      ```

      Using `with` it turns this into:

      ```javascript
      with (a.b.c) {
        greeting = "welcome";
        age = 32;
      }
      ```

      But this `with` statement creates performance problems since one cannot predict whether an argument will refer to a real variable or to a property inside the with argument.

      **[⬆ Back to Top](#table-of-contents)**

303.  ### What is the output of below for loops

      ```javascript
      for (var i = 0; i < 4; i++) {
        // global scope
        setTimeout(() => console.log(i));
      }

      for (let i = 0; i < 4; i++) {
        // block scope
        setTimeout(() => console.log(i));
      }
      ```

      The output of the above for loops is 4 4 4 4 and 0 1 2 3

      **Explanation:** Due to the event queue/loop of javascript, the `setTimeout` callback function is called after the loop has been executed. Since the variable i is declared with the `var` keyword it became a global variable and the value was equal to 4 using iteration when the time `setTimeout` function is invoked. Hence, the output of the first loop is `4 4 4 4`.

      Whereas in the second loop, the variable i is declared as the `let` keyword it becomes a block scoped variable and it holds a new value(0, 1 ,2 3) for each iteration. Hence, the output of the first loop is `0 1 2 3`.

      **[⬆ Back to Top](#table-of-contents)**

304.  ### List down some of the features of ES6

      Below are the list of some new features of ES6,

      1.  Support for constants or immutable variables
      2.  Block-scope support for variables, constants and functions
      3.  Arrow functions
      4.  Default parameters
      5.  Rest and Spread Parameters
      6.  Template Literals
      7.  Multi-line Strings
      8.  Destructuring Assignment
      9.  Enhanced Object Literals
      10. Promises
      11. Classes
      12. Modules

      **[⬆ Back to Top](#table-of-contents)**

305.  ### What is ES6

      ES6 is the sixth edition of the javascript language and it was released in June 2015. It was initially known as ECMAScript 6 (ES6) and later renamed to ECMAScript 2015. Almost all the modern browsers support ES6 but for the old browsers there are many transpilers, like Babel.js etc.

      **[⬆ Back to Top](#table-of-contents)**

306.  ### Can I redeclare let and const variables

      No, you cannot redeclare let and const variables. If you do, it throws below error

      ```bash
      Uncaught SyntaxError: Identifier 'someVariable' has already been declared
      ```

      **Explanation:** The variable declaration with `var` keyword refers to a function scope and the variable is treated as if it were declared at the top of the enclosing scope due to hoisting feature. So all the multiple declarations contributing to the same hoisted variable without any error. Let's take an example of re-declaring variables in the same scope for both var and let/const variables.

      ```javascript
      var name = "John";
      function myFunc() {
        var name = "Nick";
        var name = "Abraham"; // Re-assigned in the same function block
        alert(name); // Abraham
      }
      myFunc();
      alert(name); // John
      ```

      The block-scoped multi-declaration throws syntax error,

      ```javascript
      let name = "John";
      function myFunc() {
        let name = "Nick";
        let name = "Abraham"; // Uncaught SyntaxError: Identifier 'name' has already been declared
        alert(name);
      }

      myFunc();
      alert(name);
      ```

      **[⬆ Back to Top](#table-of-contents)**

307.  ### Is const variable makes the value immutable

      No, the const variable doesn't make the value immutable. But it disallows subsequent assignments(i.e, You can declare with assignment but can't assign another value later)

      ```javascript
      const userList = [];
      userList.push("John"); // Can mutate even though it can't re-assign
      console.log(userList); // ['John']
      ```

      **[⬆ Back to Top](#table-of-contents)**

308.  ### What are default parameters

      In ES5, we need to depend on logical OR operators to handle default values of function parameters. Whereas in ES6, Default function parameters feature allows parameters to be initialized with default values if no value or undefined is passed. Let's compare the behavior with an examples,

      ```javascript
      //ES5
      var calculateArea = function (height, width) {
        height = height || 50;
        width = width || 60;

        return width * height;
      };
      console.log(calculateArea()); //300
      ```

      The default parameters makes the initialization more simpler,

      ```javascript
      //ES6
      var calculateArea = function (height = 50, width = 60) {
        return width * height;
      };

      console.log(calculateArea()); //300
      ```

      **[⬆ Back to Top](#table-of-contents)**

309.  ### What are template literals

      Template literals or template strings are string literals allowing embedded expressions. These are enclosed by the back-tick (`) character instead of double or single quotes.
      In ES6, this feature enables using dynamic expressions as below,

      ```javascript
      var greeting = `Welcome to JS World, Mr. ${firstName} ${lastName}.`;
      ```

      In ES5, you need break string like below,

      ```javascript
      var greeting = 'Welcome to JS World, Mr. ' + firstName + ' ' + lastName.`
      ```

      **Note:** You can use multi-line strings and string interpolation features with template literals.

      **[⬆ Back to Top](#table-of-contents)**

310.  ### How do you write multi-line strings in template literals

      In ES5, you would have to use newline escape characters('\\n') and concatenation symbols(+) in order to get multi-line strings.

      ```javascript
      console.log("This is string sentence 1\n" + "This is string sentence 2");
      ```

      Whereas in ES6, You don't need to mention any newline sequence character,

      ```javascript
      console.log(`This is string sentence
      'This is string sentence 2`);
      ```

      **[⬆ Back to Top](#table-of-contents)**

311.  ### What are nesting templates

      The nesting template is a feature supported within template literals syntax to allow inner backticks inside a placeholder ${ } within the template. For example, the below nesting template is used to display the icons based on user permissions whereas outer template checks for platform type,

      ```javascript
      const iconStyles = `icon ${
        isMobilePlatform()
          ? ""
          : `icon-${user.isAuthorized ? "submit" : "disabled"}`
      }`;
      ```

      You can write the above use case without nesting template features as well. However, the nesting template feature is more compact and readable.

      ```javascript
      //Without nesting templates
      const iconStyles = `icon ${
        isMobilePlatform()
          ? ""
          : user.isAuthorized
          ? "icon-submit"
          : "icon-disabled"
      }`;
      ```

      **[⬆ Back to Top](#table-of-contents)**

312.  ### What are tagged templates

      Tagged templates are the advanced form of templates in which tags allow you to parse template literals with a function. The tag function accepts the first parameter as an array of strings and remaining parameters as expressions. This function can also return manipulated strings based on parameters. Let's see the usage of this tagged template behavior of an IT professional skill set in an organization,

      ```javascript
      var user1 = "John";
      var skill1 = "JavaScript";
      var experience1 = 15;

      var user2 = "Kane";
      var skill2 = "JavaScript";
      var experience2 = 5;

      function myInfoTag(strings, userExp, experienceExp, skillExp) {
        var str0 = strings[0]; // "Mr/Ms. "
        var str1 = strings[1]; // " is a/an "
        var str2 = strings[2]; // "in"

        var expertiseStr;
        if (experienceExp > 10) {
          expertiseStr = "expert developer";
        } else if (skillExp > 5 && skillExp <= 10) {
          expertiseStr = "senior developer";
        } else {
          expertiseStr = "junior developer";
        }

        return `${str0}${userExp}${str1}${expertiseStr}${str2}${skillExp}`;
      }

      var output1 = myInfoTag`Mr/Ms. ${user1} is a/an ${experience1} in ${skill1}`;
      var output2 = myInfoTag`Mr/Ms. ${user2} is a/an ${experience2} in ${skill2}`;

      console.log(output1); // Mr/Ms. John is a/an expert developer in JavaScript
      console.log(output2); // Mr/Ms. Kane is a/an junior developer in JavaScript
      ```

      **[⬆ Back to Top](#table-of-contents)**

313.  ### What are raw strings

      ES6 provides a raw strings feature using the `String.raw()` method which is used to get the raw string form of template strings. This feature allows you to access the raw strings as they were entered, without processing escape sequences. For example, the usage would be as below,

      ```javascript
      var calculationString = String.raw`The sum of numbers is \n${
        1 + 2 + 3 + 4
      }!`;
      console.log(calculationString); // The sum of numbers is \n10!
      ```

      If you don't use raw strings, the newline character sequence will be processed by displaying the output in multiple lines

      ```javascript
      var calculationString = `The sum of numbers is \n${1 + 2 + 3 + 4}!`;
      console.log(calculationString);
      // The sum of numbers is
      // 10!
      ```

      Also, the raw property is available on the first argument to the tag function

      ```javascript
      function tag(strings) {
        console.log(strings.raw[0]);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

314.  ### What is destructuring assignment

      The destructuring assignment is a JavaScript expression that makes it possible to unpack values from arrays or properties from objects into distinct variables.
      Let's get the month values from an array using destructuring assignment

      ```javascript
      var [one, two, three] = ["JAN", "FEB", "MARCH"];

      console.log(one); // "JAN"
      console.log(two); // "FEB"
      console.log(three); // "MARCH"
      ```

      and you can get user properties of an object using destructuring assignment,

      ```javascript
      var { name, age } = { name: "John", age: 32 };

      console.log(name); // John
      console.log(age); // 32
      ```

      **[⬆ Back to Top](#table-of-contents)**

315.  ### What are default values in destructuring assignment

      A variable can be assigned a default value when the value unpacked from the array or object is undefined during destructuring assignment. It helps to avoid setting default values separately for each assignment. Let's take an example for both arrays and object use cases,

      **Arrays destructuring:**

      ```javascript
      var x, y, z;

      [x = 2, y = 4, z = 6] = [10];
      console.log(x); // 10
      console.log(y); // 4
      console.log(z); // 6
      ```

      **Objects destructuring:**

      ```javascript
      var { x = 2, y = 4, z = 6 } = { x: 10 };

      console.log(x); // 10
      console.log(y); // 4
      console.log(z); // 6
      ```

      **[⬆ Back to Top](#table-of-contents)**

316.  ### How do you swap variables in destructuring assignment

      If you don't use destructuring assignment, swapping two values requires a temporary variable. Whereas using a destructuring feature, two variable values can be swapped in one destructuring expression. Let's swap two number variables in array destructuring assignment,

      ```javascript
      var x = 10,
        y = 20;

      [x, y] = [y, x];
      console.log(x); // 20
      console.log(y); // 10
      ```

      **[⬆ Back to Top](#table-of-contents)**

317.  ### What are enhanced object literals

      Object literals make it easy to quickly create objects with properties inside the curly braces. For example, it provides shorter syntax for common object property definition as below.

      ```javascript
      //ES6
      var x = 10,
        y = 20;
      obj = { x, y };
      console.log(obj); // {x: 10, y:20}
      //ES5
      var x = 10,
        y = 20;
      obj = { x: x, y: y };
      console.log(obj); // {x: 10, y:20}
      ```

      **[⬆ Back to Top](#table-of-contents)**

318.  ### What are dynamic imports

      The dynamic imports using `import()` function syntax allows us to load modules on demand by using promises or the async/await syntax. Currently this feature is in [stage4 proposal](https://github.com/tc39/proposal-dynamic-import). The main advantage of dynamic imports is reduction of our bundle's sizes, the size/payload response of our requests and overall improvements in the user experience.
      The syntax of dynamic imports would be as below,

      ```javascript
      import("./Module").then((Module) => Module.method());
      ```

      **[⬆ Back to Top](#table-of-contents)**

319.  ### What are the use cases for dynamic imports

      Below are some of the use cases of using dynamic imports over static imports,

      1.  Import a module on-demand or conditionally. For example, if you want to load a polyfill on legacy browser

      ```javascript
      if (isLegacyBrowser()) {
          import(···)
          .then(···);
      }
      ```

      1.  Compute the module specifier at runtime. For example, you can use it for internationalization.

      ```javascript
      import(`messages_${getLocale()}.js`).then(···);
      ```

      1.  Import a module from within a regular script instead a module.

      **[⬆ Back to Top](#table-of-contents)**

320.  ### What are typed arrays

      Typed arrays are array-like objects from ECMAScript 6 API for handling binary data. JavaScript provides 8 Typed array types,

      1.  Int8Array: An array of 8-bit signed integers
      2.  Int16Array: An array of 16-bit signed integers
      3.  Int32Array: An array of 32-bit signed integers
      4.  Uint8Array: An array of 8-bit unsigned integers
      5.  Uint16Array: An array of 16-bit unsigned integers
      6.  Uint32Array: An array of 32-bit unsigned integers
      7.  Float32Array: An array of 32-bit floating point numbers
      8.  Float64Array: An array of 64-bit floating point numbers

      For example, you can create an array of 8-bit signed integers as below

      ```javascript
      const a = new Int8Array();
      // You can pre-allocate n bytes
      const bytes = 1024;
      const a = new Int8Array(bytes);
      ```

      **[⬆ Back to Top](#table-of-contents)**

321.  ### What are the advantages of module loaders

      The module loaders provides the below features,

      1.  Dynamic loading
      2.  State isolation
      3.  Global namespace isolation
      4.  Compilation hooks
      5.  Nested virtualization

      **[⬆ Back to Top](#table-of-contents)**

322.  ### What is collation

      Collation is used for sorting a set of strings and searching within a set of strings. It is parameterized by locale and aware of Unicode. Let's take comparison and sorting features,

      1.  **Comparison:**

      ```javascript
      var list = ["ä", "a", "z"]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
      var l10nDE = new Intl.Collator("de");
      var l10nSV = new Intl.Collator("sv");
      console.log(l10nDE.compare("ä", "z") === -1); // true
      console.log(l10nSV.compare("ä", "z") === +1); // true
      ```

      1.  **Sorting:**

      ```javascript
      var list = ["ä", "a", "z"]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
      var l10nDE = new Intl.Collator("de");
      var l10nSV = new Intl.Collator("sv");
      console.log(list.sort(l10nDE.compare)); // [ "a", "ä", "z" ]
      console.log(list.sort(l10nSV.compare)); // [ "a", "z", "ä" ]
      ```

      **[⬆ Back to Top](#table-of-contents)**

323.  ### What is for...of statement

      The for...of statement creates a loop iterating over iterable objects or elements such as built-in String, Array, Array-like objects (like arguments or NodeList), TypedArray, Map, Set, and user-defined iterables. The basic usage of for...of statement on arrays would be as below,

      ```javascript
      let arrayIterable = [10, 20, 30, 40, 50];

      for (let value of arrayIterable) {
        value++;
        console.log(value); // 11 21 31 41 51
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

324.  ### What is the output of below spread operator array

      ```javascript
      [..."John Resig"];
      ```

      The output of the array is ['J', 'o', 'h', 'n', '', 'R', 'e', 's', 'i', 'g']
      **Explanation:** The string is an iterable type and the spread operator within an array maps every character of an iterable to one element. Hence, each character of a string becomes an element within an Array.

      **[⬆ Back to Top](#table-of-contents)**

325.  ### Is PostMessage secure

      Yes, postMessages can be considered very secure as long as the programmer/developer is careful about checking the origin and source of an arriving message. But if you try to send/receive a message without verifying its source will create cross-site scripting attacks.

      **[⬆ Back to Top](#table-of-contents)**

326.  ### What are the problems with postmessage target origin as wildcard

      The second argument of postMessage method specifies which origin is allowed to receive the message. If you use the wildcard “\*” as an argument then any origin is allowed to receive the message. In this case, there is no way for the sender window to know if the target window is at the target origin when sending the message. If the target window has been navigated to another origin, the other origin would receive the data. Hence, this may lead to XSS vulnerabilities.

      ```javascript
      targetWindow.postMessage(message, "*");
      ```

      **[⬆ Back to Top](#table-of-contents)**

327.  ### How do you avoid receiving postMessages from attackers

      Since the listener listens for any message, an attacker can trick the application by sending a message from the attacker’s origin, which gives an impression that the receiver received the message from the actual sender’s window. You can avoid this issue by validating the origin of the message on the receiver's end using the “message.origin” attribute. For examples, let's check the sender's origin [http://www.some-sender.com](http://www.some-sender.com) on receiver side [www.some-receiver.com](www.some-receiver.com),

      ```javascript
      //Listener on http://www.some-receiver.com/
      window.addEventListener("message", function(message){
          if(/^http://www\.some-sender\.com$/.test(message.origin)){
               console.log('You received the data from valid sender', message.data);
         }
      });
      ```

      **[⬆ Back to Top](#table-of-contents)**

328.  ### Can I avoid using postMessages completely

      You cannot avoid using postMessages completely(or 100%). Even though your application doesn’t use postMessage considering the risks, a lot of third party scripts use postMessage to communicate with the third party service. So your application might be using postMessage without your knowledge.

      **[⬆ Back to Top](#table-of-contents)**

329.  ### Is postMessages synchronous

      The postMessages are synchronous in IE8 browser but they are asynchronous in IE9 and all other modern browsers (i.e, IE9+, Firefox, Chrome, Safari).Due to this asynchronous behaviour, we use a callback mechanism when the postMessage is returned.

      **[⬆ Back to Top](#table-of-contents)**

330.  ### What paradigm is Javascript

      JavaScript is a multi-paradigm language, supporting imperative/procedural programming, Object-Oriented Programming and functional programming. JavaScript supports Object-Oriented Programming with prototypical inheritance.

      **[⬆ Back to Top](#table-of-contents)**

331.  ### What is the difference between internal and external javascript

      **Internal JavaScript:** It is the source code within the script tag.
      **External JavaScript:** The source code is stored in an external file(stored with .js extension) and referred with in the tag.

      **[⬆ Back to Top](#table-of-contents)**

332.  ### Is JavaScript faster than server side script

      Yes, JavaScript is faster than server side scripts. Because JavaScript is a client-side script it does not require any web server’s help for its computation or calculation. So JavaScript is always faster than any server-side script like ASP, PHP, etc.

      **[⬆ Back to Top](#table-of-contents)**

333.  ### How do you get the status of a checkbox

      You can apply the `checked` property on the selected checkbox in the DOM. If the value is `true` it means the checkbox is checked, otherwise it is unchecked. For example, the below HTML checkbox element can be access using javascript as below:

      ```html
      <input type="checkbox" id="checkboxname" value="Agree" /> Agree the
      conditions<br />
      ```

      ```javascript
      console.log(document.getElementById(‘checkboxname’).checked); // true or false
      ```

      **[⬆ Back to Top](#table-of-contents)**

334.  ### What is the purpose of double tilde operator

      The double tilde operator(~~) is known as double NOT bitwise operator. This operator is a slightly quicker substitute for Math.floor().

      **[⬆ Back to Top](#table-of-contents)**

335.  ### How do you convert character to ASCII code

      You can use the `String.prototype.charCodeAt()` method to convert string characters to ASCII numbers. For example, let's find ASCII code for the first letter of 'ABC' string,

      ```javascript
      "ABC".charCodeAt(0); // returns 65
      ```

      Whereas `String.fromCharCode()` method converts numbers to equal ASCII characters.

      ```javascript
      String.fromCharCode(65, 66, 67); // returns 'ABC'
      ```

      **[⬆ Back to Top](#table-of-contents)**

336.  ### What is ArrayBuffer

      An ArrayBuffer object is used to represent a generic, fixed-length raw binary data buffer. You can create it as below,

      ```javascript
      let buffer = new ArrayBuffer(16); // create a buffer of length 16
      alert(buffer.byteLength); // 16
      ```

      To manipulate an ArrayBuffer, we need to use a “view” object.

      ```javascript
      //Create a DataView referring to the buffer
      let view = new DataView(buffer);
      ```

      **[⬆ Back to Top](#table-of-contents)**

337.  ### What is the output of below string expression

      ```javascript
      console.log("Welcome to JS world"[0]);
      ```

      The output of the above expression is "W".
      **Explanation:** The bracket notation with specific index on a string returns the character at a specific location. Hence, it returns the character "W" of the string. Since this is not supported in IE7 and below versions, you may need to use the .charAt() method to get the desired result.

      **[⬆ Back to Top](#table-of-contents)**

338.  ### What is the purpose of Error object

      The Error constructor creates an error object and the instances of error objects are thrown when runtime errors occur. The Error object can also be used as a base object for user-defined exceptions. The syntax of error object would be as below,

      ```javascript
      new Error([message[, fileName[, lineNumber]]])
      ```

      You can throw user defined exceptions or errors using Error object in try...catch block as below,

      ```javascript
      try {
        if (withdraw > balance)
          throw new Error("Oops! You don't have enough balance");
      } catch (e) {
        console.log(e.name + ": " + e.message);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

339.  ### What is the purpose of EvalError object

      The EvalError object indicates an error regarding the global `eval()` function. Even though this exception is not thrown by JavaScript anymore, the EvalError object remains for compatibility. The syntax of this expression would be as below,

      ```javascript
      new EvalError([message[, fileName[, lineNumber]]])
      ```

      You can throw EvalError with in try...catch block as below,

      ```javascript
      try {
        throw new EvalError('Eval function error', 'someFile.js', 100);
      } catch (e) {
        console.log(e.message, e.name, e.fileName);              // "Eval function error", "EvalError", "someFile.js"
      ```

      **[⬆ Back to Top](#table-of-contents)**

340.  ### What are the list of cases error thrown from non-strict mode to strict mode

      When you apply 'use strict'; syntax, some of the below cases will throw a SyntaxError before executing the script

      1.  When you use Octal syntax

      ```javascript
      var n = 022;
      ```

      1.  Using `with` statement
      2.  When you use delete operator on a variable name
      3.  Using eval or arguments as variable or function argument name
      4.  When you use newly reserved keywords
      5.  When you declare a function in a block

      ```javascript
      if (someCondition) {
        function f() {}
      }
      ```

      Hence, the errors from above cases are helpful to avoid errors in development/production environments.

      **[⬆ Back to Top](#table-of-contents)**

341.  ### Do all objects have prototypes

      No. All objects have prototypes except for the base object which is created by the user, or an object that is created using the new keyword.

      **[⬆ Back to Top](#table-of-contents)**

342.  ### What is the difference between a parameter and an argument

      Parameter is the variable name of a function definition whereas an argument represents the value given to a function when it is invoked. Let's explain this with a simple function

      ```javascript
      function myFunction(parameter1, parameter2, parameter3) {
        console.log(arguments[0]); // "argument1"
        console.log(arguments[1]); // "argument2"
        console.log(arguments[2]); // "argument3"
      }
      myFunction("argument1", "argument2", "argument3");
      ```

      **[⬆ Back to Top](#table-of-contents)**

343.  ### What is the purpose of some method in arrays

      The some() method is used to test whether at least one element in the array passes the test implemented by the provided function. The method returns a boolean value. Let's take an example to test for any odd elements,

      ```javascript
      var array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

      var odd = (element) => element % 2 !== 0;

      console.log(array.some(odd)); // true (the odd element exists)
      ```

      **[⬆ Back to Top](#table-of-contents)**

344.  ### How do you combine two or more arrays

      The concat() method is used to join two or more arrays by returning a new array containing all the elements. The syntax would be as below,

      ```javascript
      array1.concat(array2, array3, ..., arrayX)
      ```

      Let's take an example of array's concatenation with veggies and fruits arrays,

      ```javascript
      var veggies = ["Tomato", "Carrot", "Cabbage"];
      var fruits = ["Apple", "Orange", "Pears"];
      var veggiesAndFruits = veggies.concat(fruits);
      console.log(veggiesAndFruits); // Tomato, Carrot, Cabbage, Apple, Orange, Pears
      ```

      **[⬆ Back to Top](#table-of-contents)**

345.  ### What is the difference between Shallow and Deep copy

      There are two ways to copy an object,

      **Shallow Copy:**
      Shallow copy is a bitwise copy of an object. A new object is created that has an exact copy of the values in the original object. If any of the fields of the object are references to other objects, just the reference addresses are copied i.e., only the memory address is copied.

      **Example**

      ```javascript
      var empDetails = {
        name: "John",
        age: 25,
        expertise: "Software Developer",
      };
      ```

      to create a duplicate

      ```javascript
      var empDetailsShallowCopy = empDetails; //Shallow copying!
      ```

      if we change some property value in the duplicate one like this:

      ```javascript
      empDetailsShallowCopy.name = "Johnson";
      ```

      The above statement will also change the name of `empDetails`, since we have a shallow copy. That means we're losing the original data as well.

      **Deep copy:**
      A deep copy copies all fields, and makes copies of dynamically allocated memory pointed to by the fields. A deep copy occurs when an object is copied along with the objects to which it refers.

      **Example**

      ```javascript
      var empDetails = {
        name: "John",
        age: 25,
        expertise: "Software Developer",
      };
      ```

      Create a deep copy by using the properties from the original object into new variable

      ```javascript
      var empDetailsDeepCopy = {
        name: empDetails.name,
        age: empDetails.age,
        expertise: empDetails.expertise,
      };
      ```

      Now if you change `empDetailsDeepCopy.name`, it will only affect `empDetailsDeepCopy` & not `empDetails`

      **[⬆ Back to Top](#table-of-contents)**

346.  ### How do you create specific number of copies of a string

      The `repeat()` method is used to construct and return a new string which contains the specified number of copies of the string on which it was called, concatenated together. Remember that this method has been added to the ECMAScript 2015 specification.
      Let's take an example of Hello string to repeat it 4 times,

      ```javascript
      "Hello".repeat(4); // 'HelloHelloHelloHello'
      ```

347.  ### How do you return all matching strings against a regular expression

      The `matchAll()` method can be used to return an iterator of all results matching a string against a regular expression. For example, the below example returns an array of matching string results against a regular expression,

      ```javascript
      let regexp = /Hello(\d?))/g;
      let greeting = "Hello1Hello2Hello3";

      let greetingList = [...greeting.matchAll(regexp)];

      console.log(greetingList[0]); //Hello1
      console.log(greetingList[1]); //Hello2
      console.log(greetingList[2]); //Hello3
      ```

      **[⬆ Back to Top](#table-of-contents)**

348.  ### How do you trim a string at the beginning or ending

      The `trim` method of string prototype is used to trim on both sides of a string. But if you want to trim especially at the beginning or ending of the string then you can use `trimStart/trimLeft` and `trimEnd/trimRight` methods. Let's see an example of these methods on a greeting message,

      ```javascript
      var greeting = "   Hello, Goodmorning!   ";

      console.log(greeting); // "   Hello, Goodmorning!   "
      console.log(greeting.trimStart()); // "Hello, Goodmorning!   "
      console.log(greeting.trimLeft()); // "Hello, Goodmorning!   "

      console.log(greeting.trimEnd()); // "   Hello, Goodmorning!"
      console.log(greeting.trimRight()); // "   Hello, Goodmorning!"
      ```

      **[⬆ Back to Top](#table-of-contents)**

349.  ### What is the output of below console statement with unary operator

      Let's take console statement with unary operator as given below,

      ```javascript
      console.log(+"Hello");
      ```

      The output of the above console log statement returns NaN. Because the element is prefixed by the unary operator and the JavaScript interpreter will try to convert that element into a number type. Since the conversion fails, the value of the statement results in NaN value.

      **[⬆ Back to Top](#table-of-contents)**

350.  ### Does javascript uses mixins

      Mixin is a generic object-oriented programming term - is a class containing methods that can be used by other classes without a need to inherit from it. In JavaScript we can only inherit from a single object. ie. There can be only one `[[prototype]]` for an object.

      But sometimes we require to extend more than one, to overcome this we can use Mixin which helps to copy methods to the prototype of another class.

      Say for instance, we've two classes `User` and `CleanRoom`. Suppose we need to add `CleanRoom` functionality to `User`, so that user can clean the room at demand. Here's where concept called mixins comes into picture.

      ```javascript
      // mixin
      let cleanRoomMixin = {
        cleanRoom() {
          alert(`Hello ${this.name}, your room is clean now`);
        },
        sayBye() {
          alert(`Bye ${this.name}`);
        },
      };

      // usage:
      class User {
        constructor(name) {
          this.name = name;
        }
      }

      // copy the methods
      Object.assign(User.prototype, cleanRoomMixin);

      // now User can clean the room
      new User("Dude").cleanRoom(); // Hello Dude, your room is clean now!
      ```

      **[⬆ Back to Top](#table-of-contents)**

351.  ### What is a thunk function

      A thunk is just a function which delays the evaluation of the value. It doesn’t take any arguments but gives the value whenever you invoke the thunk. i.e, It is used not to execute now but it will be sometime in the future. Let's take a synchronous example,

      ```javascript
      const add = (x, y) => x + y;

      const thunk = () => add(2, 3);

      thunk(); // 5
      ```

      **[⬆ Back to Top](#table-of-contents)**

352.  ### What are asynchronous thunks

      The asynchronous thunks are useful to make network requests. Let's see an example of network requests,

      ```javascript
      function fetchData(fn) {
        fetch("https://jsonplaceholder.typicode.com/todos/1")
          .then((response) => response.json())
          .then((json) => fn(json));
      }

      const asyncThunk = function () {
        return fetchData(function getData(data) {
          console.log(data);
        });
      };

      asyncThunk();
      ```

      The `getData` function won't be called immediately but it will be invoked only when the data is available from API endpoint. The setTimeout function is also used to make our code asynchronous. The best real time example is redux state management library which uses the asynchronous thunks to delay the actions to dispatch.

      **[⬆ Back to Top](#table-of-contents)**

353.  ### What is the output of below function calls

      **Code snippet:**

      ```javascript
      const circle = {
        radius: 20,
        diameter() {
          return this.radius * 2;
        },
        perimeter: () => 2 * Math.PI * this.radius,
      };
      ```

      ```javascript
      console.log(circle.diameter());
      console.log(circle.perimeter());
      ```

      **Output:**

      The output is 40 and NaN. Remember that diameter is a regular function, whereas the value of perimeter is an arrow function. The `this` keyword of a regular function(i.e, diameter) refers to the surrounding scope which is a class(i.e, Shape object). Whereas this keyword of perimeter function refers to the surrounding scope which is a window object. Since there is no radius property on window objects it returns an undefined value and the multiple of number value returns NaN value.

      **[⬆ Back to Top](#table-of-contents)**

354.  ### How to remove all line breaks from a string

      The easiest approach is using regular expressions to detect and replace newlines in the string. In this case, we use replace function along with string to replace with, which in our case is an empty string.

      ```javascript
      function remove_linebreaks( var message ) {
          return message.replace( /[\r\n]+/gm, "" );
      }
      ```

      In the above expression, g and m are for global and multiline flags.

      **[⬆ Back to Top](#table-of-contents)**

355.  ### What is the difference between reflow and repaint

      A _repaint_ occurs when changes are made which affect the visibility of an element, but not its layout. Examples of this include outline, visibility, or background color. A _reflow_ involves changes that affect the layout of a portion of the page (or the whole page). Resizing the browser window, changing the font, content changing (such as user typing text), using JavaScript methods involving computed styles, adding or removing elements from the DOM, and changing an element's classes are a few of the things that can trigger reflow. Reflow of an element causes the subsequent reflow of all child and ancestor elements as well as any elements following it in the DOM.

      **[⬆ Back to Top](#table-of-contents)**

356.  ### What happens with negating an array

      Negating an array with `!` character will coerce the array into a boolean. Since Arrays are considered to be truthy So negating it will return `false`.

      ```javascript
      console.log(![]); // false
      ```

      **[⬆ Back to Top](#table-of-contents)**

357.  ### What happens if we add two arrays

      If you add two arrays together, it will convert them both to strings and concatenate them. For example, the result of adding arrays would be as below,

      ```javascript
      console.log(["a"] + ["b"]); // "ab"
      console.log([] + []); // ""
      console.log(![] + []); // "false", because ![] returns false.
      ```

      **[⬆ Back to Top](#table-of-contents)**

358.  ### What is the output of prepend additive operator on falsy values

      If you prepend the additive(+) operator on falsy values(null, undefined, NaN, false, ""), the falsy value converts to a number value zero. Let's display them on browser console as below,

      ```javascript
      console.log(+null); // 0
      console.log(+undefined); // NaN
      console.log(+false); // 0
      console.log(+NaN); // NaN
      console.log(+""); // 0
      ```

      **[⬆ Back to Top](#table-of-contents)**

359.  ### How do you create self string using special characters

      The self string can be formed with the combination of `[]()!+` characters. You need to remember the below conventions to achieve this pattern.

      1.  Since Arrays are truthful values, negating the arrays will produce false: ![] === false
      2.  As per JavaScript coercion rules, the addition of arrays together will toString them: [] + [] === ""
      3.  Prepend an array with + operator will convert an array to false, the negation will make it true and finally converting the result will produce value '1': +(!(+[])) === 1

      By applying the above rules, we can derive below conditions

      ```javascript
      (![] + [] === "false" + !+[]) === 1;
      ```

      Now the character pattern would be created as below,

      ```javascript
            s               e               l               f
       ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^

       (![] + [])[3] + (![] + [])[4] + (![] + [])[2] + (![] + [])[0]
       ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^
      (![] + [])[+!+[]+!+[]+!+[]] +
      (![] + [])[+!+[]+!+[]+!+[]+!+[]] +
      (![] + [])[+!+[]+!+[]] +
      (![] + [])[+[]]
      ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
      (![]+[])[+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]]+(![]+[])[+[]]
      ```

      **[⬆ Back to Top](#table-of-contents)**

360.  ### How do you remove falsy values from an array

      You can apply the filter method on the array by passing Boolean as a parameter. This way it removes all falsy values(0, undefined, null, false and "") from the array.

      ```javascript
      const myArray = [false, null, 1, 5, undefined];
      myArray.filter(Boolean); // [1, 5] // is same as myArray.filter(x => x);
      ```

      **[⬆ Back to Top](#table-of-contents)**

361.  ### How do you get unique values of an array

      You can get unique values of an array with the combination of `Set` and rest expression/spread(...) syntax.

      ```javascript
      console.log([...new Set([1, 2, 4, 4, 3])]); // [1, 2, 4, 3]
      ```

      **[⬆ Back to Top](#table-of-contents)**

362.  ### What is destructuring aliases

      Sometimes you would like to have a destructured variable with a different name than the property name. In that case, you'll use a `: newName` to specify a name for the variable. This process is called destructuring aliases.

      ```javascript
      const obj = { x: 1 };
      // Grabs obj.x as as { otherName }
      const { x: otherName } = obj;
      ```

      **[⬆ Back to Top](#table-of-contents)**

363.  ### How do you map the array values without using map method

      You can map the array values without using the `map` method by just using the `from` method of Array. Let's map city names from Countries array,

      ```javascript
      const countries = [
        { name: "India", capital: "Delhi" },
        { name: "US", capital: "Washington" },
        { name: "Russia", capital: "Moscow" },
        { name: "Singapore", capital: "Singapore" },
        { name: "China", capital: "Beijing" },
        { name: "France", capital: "Paris" },
      ];

      const cityNames = Array.from(countries, ({ capital }) => capital);
      console.log(cityNames); // ['Delhi, 'Washington', 'Moscow', 'Singapore', 'Beijing', 'Paris']
      ```

      **[⬆ Back to Top](#table-of-contents)**

364.  ### How do you empty an array

      You can empty an array quickly by setting the array length to zero.

      ```javascript
      let cities = ["Singapore", "Delhi", "London"];
      cities.length = 0; // cities becomes []
      ```

      **[⬆ Back to Top](#table-of-contents)**

365.  ### How do you rounding numbers to certain decimals

      You can round numbers to a certain number of decimals using `toFixed` method from native javascript.

      ```javascript
      let pie = 3.141592653;
      pie = pie.toFixed(3); // 3.142
      ```

      **[⬆ Back to Top](#table-of-contents)**

366.  ### What is the easiest way to convert an array to an object

      You can convert an array to an object with the same data using spread(...) operator.

      ```javascript
      var fruits = ["banana", "apple", "orange", "watermelon"];
      var fruitsObject = { ...fruits };
      console.log(fruitsObject); // {0: "banana", 1: "apple", 2: "orange", 3: "watermelon"}
      ```

      **[⬆ Back to Top](#table-of-contents)**

367.  ### How do you create an array with some data

      You can create an array with some data or an array with the same values using `fill` method.

      ```javascript
      var newArray = new Array(5).fill("0");
      console.log(newArray); // ["0", "0", "0", "0", "0"]
      ```

      **[⬆ Back to Top](#table-of-contents)**

368.  ### What are the placeholders from console object

      Below are the list of placeholders available from console object,

      1.  %o — It takes an object,
      2.  %s — It takes a string,
      3.  %d — It is used for a decimal or integer
          These placeholders can be represented in the console.log as below

      ```javascript
      const user = { name: "John", id: 1, city: "Delhi" };
      console.log(
        "Hello %s, your details %o are available in the object form",
        "John",
        user
      ); // Hello John, your details {name: "John", id: 1, city: "Delhi"} are available in object
      ```

      **[⬆ Back to Top](#table-of-contents)**

369.  ### Is it possible to add CSS to console messages

      Yes, you can apply CSS styles to console messages similar to html text on the web page.

      ```javascript
      console.log(
        "%c The text has blue color, with large font and red background",
        "color: blue; font-size: x-large; background: red"
      );
      ```

      The text will be displayed as below,
      ![Screenshot](images/console-css.png)

      **Note:** All CSS styles can be applied to console messages.

      **[⬆ Back to Top](#table-of-contents)**

370.  ### What is the purpose of dir method of console object

      The `console.dir()` is used to display an interactive list of the properties of the specified JavaScript object as JSON.

      ```javascript
      const user = { name: "John", id: 1, city: "Delhi" };
      console.dir(user);
      ```

      The user object displayed in JSON representation
      ![Screenshot](images/console-dir.png)

      **[⬆ Back to Top](#table-of-contents)**

371.  ### Is it possible to debug HTML elements in console

      Yes, it is possible to get and debug HTML elements in the console just like inspecting elements.

      ```javascript
      const element = document.getElementsByTagName("body")[0];
      console.log(element);
      ```

      It prints the HTML element in the console,

      ![Screenshot](images/console-html.png)

      **[⬆ Back to Top](#table-of-contents)**

372.  ### How do you display data in a tabular format using console object

      The `console.table()` is used to display data in the console in a tabular format to visualize complex arrays or objects.

      ```js
      const users = [
        { name: "John", id: 1, city: "Delhi" },
        { name: "Max", id: 2, city: "London" },
        { name: "Rod", id: 3, city: "Paris" },
      ];
      console.table(users);
      ```

      The data visualized in a table format,

      ![Screenshot](images/console-table.png)
      **Not:** Remember that `console.table()` is not supported in IE.

      **[⬆ Back to Top](#table-of-contents)**

373.  ### How do you verify that an argument is a Number or not

      The combination of IsNaN and isFinite methods are used to confirm whether an argument is a number or not.

      ```javascript
      function isNumber(n) {
        return !isNaN(parseFloat(n)) && isFinite(n);
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

374.  ### How do you create copy to clipboard button

      You need to select the content(using .select() method) of the input element and execute the copy command with execCommand (i.e, execCommand('copy')). You can also execute other system commands like cut and paste.

      ```javascript
      document.querySelector("#copy-button").onclick = function () {
        // Select the content
        document.querySelector("#copy-input").select();
        // Copy to the clipboard
        document.execCommand("copy");
      };
      ```

      **[⬆ Back to Top](#table-of-contents)**

375.  ### What is the shortcut to get timestamp

      You can use `new Date().getTime()` to get the current timestamp. There is an alternative shortcut to get the value.

      ```javascript
      console.log(+new Date());
      console.log(Date.now());
      ```

      **[⬆ Back to Top](#table-of-contents)**

376.  ### How do you flattening multi dimensional arrays

      Flattening bi-dimensional arrays is trivial with Spread operator.

      ```javascript
      const biDimensionalArr = [11, [22, 33], [44, 55], [66, 77], 88, 99];
      const flattenArr = [].concat(...biDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
      ```

      But you can make it work with multi-dimensional arrays by recursive calls,

      ```javascript
      function flattenMultiArray(arr) {
        const flattened = [].concat(...arr);
        return flattened.some((item) => Array.isArray(item))
          ? flattenMultiArray(flattened)
          : flattened;
      }
      const multiDimensionalArr = [
        11,
        [22, 33],
        [44, [55, 66, [77, [88]], 99]],
      ];
      const flatArr = flattenMultiArray(multiDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
      ```

      Also you can use the `flat` method of Array.

      ```javascript
      const arr = [1, [2, 3], 4, 5, [6, 7]];
      const fllattenArr = arr.flat(); // [1, 2, 3, 4, 5, 6, 7]

      // And for multiDemensional arrays
      const multiDimensionalArr = [
        11,
        [22, 33],
        [44, [55, 66, [77, [88]], 99]],
      ];
      const oneStepFlat = multiDimensionalArr.flat(1); // [11, 22, 33, 44, [55, 66, [77, [88]], 99]]
      const towStep = multiDimensionalArr.flat(2); // [11, 22, 33, 44, 55, 66, [77, [88]], 99]
      const fullyFlatArray = multiDimensionalArr.flat(Infinity); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
      ```

      **[⬆ Back to Top](#table-of-contents)**

377.  ### What is the easiest multi condition checking

      You can use `indexOf` to compare input with multiple values instead of checking each value as one condition.

      ```javascript
      // Verbose approach
      if (
        input === "first" ||
        input === 1 ||
        input === "second" ||
        input === 2
      ) {
        someFunction();
      }
      // Shortcut
      if (["first", 1, "second", 2].indexOf(input) !== -1) {
        someFunction();
      }
      ```

      **[⬆ Back to Top](#table-of-contents)**

378.  ### How do you capture browser back button

      The `beforeunload` event is triggered when the window, the document and its resources are about to be unloaded. This event is helpful to warn users about losing the current data and detect back button event.

      ```javascript
      window.addEventListener("beforeunload", () => {
        console.log("Clicked browser back button");
      });
      ```

      You can also use `popstate` event to detect the browser back button.
      **Note:** The history entry has been activated using `history.pushState` method.

      ```javascript
      window.addEventListener("popstate", () => {
        console.log("Clicked browser back button");
        box.style.backgroundColor = "white";
      });

      const box = document.getElementById("div");

      box.addEventListener("click", () => {
        box.style.backgroundColor = "blue";
        window.history.pushState({}, null, null);
      });
      ```


    In the preceeding code, When the box element clicked, its background color appears in blue color and changed to while color upon clicking the browser back button using `popstate` event handler. The `state` property of `popstate` contains the copy of history entry's state object.

     **[⬆ Back to Top](#table-of-contents)**

379. ### How do you disable right click in the web page

     The right click on the page can be disabled by returning false from the `oncontextmenu` attribute on the body element.

     ```html
     <body oncontextmenu="return false;"></body>
     ```

     **[⬆ Back to Top](#table-of-contents)**

380. ### What are wrapper objects

     Primitive Values like string,number and boolean don't have properties and methods but they are temporarily converted or coerced to an object(Wrapper object) when you try to perform actions on them. For example, if you apply toUpperCase() method on a primitive string value, it does not throw an error but returns uppercase of the string.

     ```javascript
     let name = "john";

     console.log(name.toUpperCase()); // Behind the scenes treated as console.log(new String(name).toUpperCase());
     ```

     i.e, Every primitive except null and undefined have Wrapper Objects and the list of wrapper objects are String,Number,Boolean,Symbol and BigInt.

     **[⬆ Back to Top](#table-of-contents)**

381. ### What is AJAX

     AJAX stands for Asynchronous JavaScript and XML and it is a group of related technologies(HTML, CSS, JavaScript, XMLHttpRequest API etc) used to display data asynchronously. i.e. We can send data to the server and get data from the server without reloading the web page.

     **[⬆ Back to Top](#table-of-contents)**

382. ### What are the different ways to deal with Asynchronous Code

     Below are the list of different ways to deal with Asynchronous code.

     1. Callbacks
     2. Promises
     3. Async/await
     4. Third-party libraries such as async.js,bluebird etc

     **[⬆ Back to Top](#table-of-contents)**

383. ### How to cancel a fetch request

     Until a few days back, One shortcoming of native promises is no direct way to cancel a fetch request. But the new `AbortController` from js specification allows you to use a signal to abort one or multiple fetch calls.
     The basic flow of cancelling a fetch request would be as below,

     1. Create an `AbortController` instance
     2. Get the signal property of an instance and pass the signal as a fetch option for signal
     3. Call the AbortController's abort property to cancel all fetches that use that signal
        For example, let's pass the same signal to multiple fetch calls will cancel all requests with that signal,

     ```javascript
     const controller = new AbortController();
     const { signal } = controller;

     fetch("http://localhost:8000", { signal })
       .then((response) => {
         console.log(`Request 1 is complete!`);
       })
       .catch((e) => {
         if (e.name === "AbortError") {
           // We know it's been canceled!
         }
       });

     fetch("http://localhost:8000", { signal })
       .then((response) => {
         console.log(`Request 2 is complete!`);
       })
       .catch((e) => {
         if (e.name === "AbortError") {
           // We know it's been canceled!
         }
       });

     // Wait 2 seconds to abort both requests
     setTimeout(() => controller.abort(), 2000);
     ```

     **[⬆ Back to Top](#table-of-contents)**

384. ### What is web speech API

     Web speech API is used to enable modern browsers recognize and synthesize speech(i.e, voice data into web apps). This API has been introduced by W3C Community in the year 2012. It has two main parts,

     1. **SpeechRecognition (Asynchronous Speech Recognition or Speech-to-Text):** It provides the ability to recognize voice context from an audio input and respond accordingly. This is accessed by the `SpeechRecognition` interface.
        The below example shows on how to use this API to get text from speech,

     ```javascript
     window.SpeechRecognition =
       window.webkitSpeechRecognition || window.SpeechRecognition; // webkitSpeechRecognition for Chrome and SpeechRecognition for FF
     const recognition = new window.SpeechRecognition();
     recognition.onresult = (event) => {
       // SpeechRecognitionEvent type
       const speechToText = event.results[0][0].transcript;
       console.log(speechToText);
     };
     recognition.start();
     ```

     In this API, browser is going to ask you for permission to use your microphone

     1. **SpeechSynthesis (Text-to-Speech):** It provides the ability to recognize voice context from an audio input and respond. This is accessed by the `SpeechSynthesis` interface.
        For example, the below code is used to get voice/speech from text,

     ```javascript
     if ("speechSynthesis" in window) {
       var speech = new SpeechSynthesisUtterance("Hello World!");
       speech.lang = "en-US";
       window.speechSynthesis.speak(speech);
     }
     ```

     The above examples can be tested on chrome(33+) browser's developer console.
     **Note:** This API is still a working draft and only available in Chrome and Firefox browsers(ofcourse Chrome only implemented the specification)

     **[⬆ Back to Top](#table-of-contents)**

385. ### What is minimum timeout throttling

     Both browser and NodeJS javascript environments throttles with a minimum delay that is greater than 0ms. That means even though setting a delay of 0ms will not happen instantaneously.
     **Browsers:** They have a minimum delay of 4ms. This throttle occurs when successive calls are triggered due to callback nesting(certain depth) or after a certain number of successive intervals.
     Note: The older browsers have a minimum delay of 10ms.
     **Nodejs:** They have a minimum delay of 1ms. This throttle happens when the delay is larger than 2147483647 or less than 1.
     The best example to explain this timeout throttling behavior is the order of below code snippet.

     ```javascript
     function runMeFirst() {
       console.log("My script is initialized");
     }
     setTimeout(runMeFirst, 0);
     console.log("Script loaded");
     ```

     and the output would be in

     ```cmd
     Script loaded
     My script is initialized
     ```

     If you don't use `setTimeout`, the order of logs will be sequential.

     ```javascript
     function runMeFirst() {
       console.log("My script is initialized");
     }
     runMeFirst();
     console.log("Script loaded");
     ```

     and the output is,

     ```cmd
     My script is initialized
     Script loaded
     ```

     **[⬆ Back to Top](#table-of-contents)**

386. ### How do you implement zero timeout in modern browsers

     You can't use setTimeout(fn, 0) to execute the code immediately due to minimum delay of greater than 0ms. But you can use window.postMessage() to achieve this behavior.

     **[⬆ Back to Top](#table-of-contents)**

387. ### What are tasks in event loop

     A task is any javascript code/program which is scheduled to be run by the standard mechanisms such as initially starting to run a program, run an event callback, or an interval or timeout being fired. All these tasks are scheduled on a task queue.
     Below are the list of use cases to add tasks to the task queue,

     1. When a new javascript program is executed directly from console or running by the `<script>` element, the task will be added to the task queue.
     2. When an event fires, the event callback added to task queue
     3. When a setTimeout or setInterval is reached, the corresponding callback added to task queue

     **[⬆ Back to Top](#table-of-contents)**

388. ### What is microtask

     Microtask is the javascript code which needs to be executed immediately after the currently executing task/microtask is completed. They are kind of blocking in nature. i.e, The main thread will be blocked until the microtask queue is empty.
     The main sources of microtasks are Promise.resolve, Promise.reject, MutationObservers, IntersectionObservers etc

     **Note:** All of these microtasks are processed in the same turn of the event loop.
     **[⬆ Back to Top](#table-of-contents)**

389. ### What are different event loops

     In JavaScript, there are multiple event loops that can be used depending on the context of your application. The most common event loops are:

390. The Browser Event Loop
391. The Node.js Event Loop


    - Browser Event Loop: The Browser Event Loop is used in client-side JavaScript applications and is responsible for handling events that occur within the browser environment, such as user interactions (clicks, keypresses, etc.), HTTP requests, and other asynchronous actions.

    - The Node.js Event Loop is used in server-side JavaScript applications and is responsible for handling events that occur within the Node.js runtime environment, such as file I/O, network I/O, and other asynchronous actions.

     **[⬆ Back to Top](#table-of-contents)**

390. ### What is the purpose of queueMicrotask

     The `queueMicrotask` function is used to schedule a microtask, which is a function that will be executed asynchronously in the microtask queue. The purpose of `queueMicrotask` is to ensure that a function is executed after the current task has finished, but before the browser performs any rendering or handles user events.

     Example:

     ```javascript
     console.log("Start"); //1

     queueMicrotask(() => {
       console.log("Inside microtask"); // 3
     });

     console.log("End"); //2
     ```

     By using queueMicrotask, you can ensure that certain tasks or callbacks are executed at the earliest opportunity during the JavaScript event loop, making it useful for performing work that needs to be done asynchronously but with higher priority than regular `setTimeout` or `setInterval` callbacks.

     **[⬆ Back to Top](#table-of-contents)**

391. ### How do you use javascript libraries in typescript file

     It is known that not all JavaScript libraries or frameworks have TypeScript declaration files. But if you still want to use libraries or frameworks in our TypeScript files without getting compilation errors, the only solution is `declare` keyword along with a variable declaration. For example, let's imagine you have a library called `customLibrary` that doesn’t have a TypeScript declaration and have a namespace called `customLibrary` in the global namespace. You can use this library in typescript code as below,

     ```javascript
     declare var customLibrary;
     ```

     In the runtime, typescript will provide the type to the `customLibrary` variable as `any` type. The another alternative without using declare keyword is below

     ```javascript
     var customLibrary: any;
     ```

     **[⬆ Back to Top](#table-of-contents)**

392. ### What are the differences between promises and observables

     Some of the major difference in a tabular form

     | Promises                                                           | Observables                                                                              |
     | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
     | Emits only a single value at a time                                | Emits multiple values over a period of time(stream of values ranging from 0 to multiple) |
     | Eager in nature; they are going to be called immediately           | Lazy in nature; they require subscription to be invoked                                  |
     | Promise is always asynchronous even though it resolved immediately | Observable can be either synchronous or asynchronous                                     |
     | Doesn't provide any operators                                      | Provides operators such as map, forEach, filter, reduce, retry, and retryWhen etc        |
     | Cannot be canceled                                                 | Canceled by using unsubscribe() method                                                   |

     **[⬆ Back to Top](#table-of-contents)**

393. ### What is heap

     Heap(Or memory heap) is the memory location where objects are stored when we define variables. i.e, This is the place where all the memory allocations and de-allocation take place. Both heap and call-stack are two containers of JS runtime.
     Whenever runtime comes across variables and function declarations in the code it stores them in the Heap.

     ![Screenshot](images/heap.png)

     **[⬆ Back to Top](#table-of-contents)**

394. ### What is an event table

     Event Table is a data structure that stores and keeps track of all the events which will be executed asynchronously like after some time interval or after the resolution of some API requests. i.e Whenever you call a setTimeout function or invoke async operation, it is added to the Event Table.
     It doesn't not execute functions on it’s own. The main purpose of the event table is to keep track of events and send them to the Event Queue as shown in the below diagram.

     ![Screenshot](images/event-table.png)

     **[⬆ Back to Top](#table-of-contents)**

395. ### What is a microTask queue

     Microtask Queue is the new queue where all the tasks initiated by promise objects get processed before the callback queue.
     The microtasks queue are processed before the next rendering and painting jobs. But if these microtasks are running for a long time then it leads to visual degradation.

     **[⬆ Back to Top](#table-of-contents)**

396. ### What is the difference between shim and polyfill

     A shim is a library that brings a new API to an older environment, using only the means of that environment. It isn't necessarily restricted to a web application. For example, es5-shim.js is used to emulate ES5 features on older browsers (mainly pre IE9).
     Whereas polyfill is a piece of code (or plugin) that provides the technology that you, the developer, expect the browser to provide natively.
     In a simple sentence, A polyfill is a shim for a browser API.

     **[⬆ Back to Top](#table-of-contents)**

397. ### How do you detect primitive or non primitive value type

     In JavaScript, primitive types include boolean, string, number, BigInt, null, Symbol and undefined. Whereas non-primitive types include the Objects. But you can easily identify them with the below function,

     ```javascript
     var myPrimitive = 30;
     var myNonPrimitive = {};
     function isPrimitive(val) {
       return Object(val) !== val;
     }

     isPrimitive(myPrimitive);
     isPrimitive(myNonPrimitive);
     ```

     If the value is a primitive data type, the Object constructor creates a new wrapper object for the value. But If the value is a non-primitive data type (an object), the Object constructor will give the same object.

     **[⬆ Back to Top](#table-of-contents)**

398. ### What is babel

     Babel is a JavaScript transpiler to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments. Some of the main features are listed below,

     1. Transform syntax
     2. Polyfill features that are missing in your target environment (using @babel/polyfill)
     3. Source code transformations (or codemods)

     **[⬆ Back to Top](#table-of-contents)**

399. ### Is Node.js completely single threaded

     Node is a single thread, but some of the functions included in the Node.js standard library(e.g, fs module functions) are not single threaded. i.e, Their logic runs outside of the Node.js single thread to improve the speed and performance of a program.

     **[⬆ Back to Top](#table-of-contents)**

400. ### What are the common use cases of observables

     Some of the most common use cases of observables are web sockets with push notifications, user input changes, repeating intervals, etc

     **[⬆ Back to Top](#table-of-contents)**

401. ### What is RxJS

     RxJS (Reactive Extensions for JavaScript) is a library for implementing reactive programming using observables that makes it easier to compose asynchronous or callback-based code. It also provides utility functions for creating and working with observables.

     **[⬆ Back to Top](#table-of-contents)**

402. ### What is the difference between Function constructor and function declaration

     The functions which are created with `Function constructor` do not create closures to their creation contexts but they are always created in the global scope. i.e, the function can access its own local variables and global scope variables only. Whereas function declarations can access outer function variables(closures) too.

     Let's see this difference with an example,

     **Function Constructor:**

     ```javascript
     var a = 100;
     function createFunction() {
       var a = 200;
       return new Function("return a;");
     }
     console.log(createFunction()()); // 100
     ```

     **Function declaration:**

     ```javascript
     var a = 100;
     function createFunction() {
       var a = 200;
       return function func() {
         return a;
       };
     }
     console.log(createFunction()()); // 200
     ```

     **[⬆ Back to Top](#table-of-contents)**

403. ### What is a Short circuit condition

     Short circuit conditions are meant for condensed way of writing simple if statements. Let's demonstrate the scenario using an example. If you would like to login to a portal with an authentication condition, the expression would be as below,

     ```javascript
     if (authenticate) {
       loginToPorta();
     }
     ```

     Since the javascript logical operators evaluated from left to right, the above expression can be simplified using && logical operator

     ```javascript
     authenticate && loginToPorta();
     ```

     **[⬆ Back to Top](#table-of-contents)**

404. ### What is the easiest way to resize an array

     The length property of an array is useful to resize or empty an array quickly. Let's apply length property on number array to resize the number of elements from 5 to 2,

     ```javascript
     var array = [1, 2, 3, 4, 5];
     console.log(array.length); // 5

     array.length = 2;
     console.log(array.length); // 2
     console.log(array); // [1,2]
     ```

     and the array can be emptied too

     ```javascript
     var array = [1, 2, 3, 4, 5];
     array.length = 0;
     console.log(array.length); // 0
     console.log(array); // []
     ```

     **[⬆ Back to Top](#table-of-contents)**

405. ### What is an observable

     An Observable is basically a function that can return a stream of values either synchronously or asynchronously to an observer over time. The consumer can get the value by calling `subscribe()` method.
     Let's look at a simple example of an Observable

     ```javascript
     import { Observable } from "rxjs";

     const observable = new Observable((observer) => {
       setTimeout(() => {
         observer.next("Message from a Observable!");
       }, 3000);
     });

     observable.subscribe((value) => console.log(value));
     ```

     ![Screenshot](images/observables.png)

     **Note:** Observables are not part of the JavaScript language yet but they are being proposed to be added to the language

     **[⬆ Back to Top](#table-of-contents)**

406. ### What is the difference between function and class declarations

     The main difference between function declarations and class declarations is `hoisting`. The function declarations are hoisted but not class declarations.

     **Classes:**

     ```javascript
     const user = new User(); // ReferenceError

     class User {}
     ```

     **Constructor Function:**

     ```javascript
     const user = new User(); // No error

     function User() {}
     ```

     **[⬆ Back to Top](#table-of-contents)**

407. ### What is an async function

     An async function is a function declared with the `async` keyword which enables asynchronous, promise-based behavior to be written in a cleaner style by avoiding promise chains. These functions can contain zero or more `await` expressions.

     Let's take a below async function example,

     ```javascript
     async function logger() {
       let data = await fetch("http://someapi.com/users"); // pause until fetch returns
       console.log(data);
     }
     logger();
     ```

     It is basically syntax sugar over ES2015 promises and generators.

     **[⬆ Back to Top](#table-of-contents)**

408. ### How do you prevent promises swallowing errors

     While using asynchronous code, JavaScript’s ES6 promises can make your life a lot easier without having callback pyramids and error handling on every second line. But Promises have some pitfalls and the biggest one is swallowing errors by default.

     Let's say you expect to print an error to the console for all the below cases,

     ```javascript
     Promise.resolve("promised value").then(function () {
       throw new Error("error");
     });

     Promise.reject("error value").catch(function () {
       throw new Error("error");
     });

     new Promise(function (resolve, reject) {
       throw new Error("error");
     });
     ```

     But there are many modern JavaScript environments that won't print any errors. You can fix this problem in different ways,

     1. **Add catch block at the end of each chain:** You can add catch block to the end of each of your promise chains

        ```javascript
        Promise.resolve("promised value")
          .then(function () {
            throw new Error("error");
          })
          .catch(function (error) {
            console.error(error.stack);
          });
        ```

        But it is quite difficult to type for each promise chain and verbose too.

     2. **Add done method:** You can replace first solution's then and catch blocks with done method

        ```javascript
        Promise.resolve("promised value").done(function () {
          throw new Error("error");
        });
        ```

        Let's say you want to fetch data using HTTP and later perform processing on the resulting data asynchronously. You can write `done` block as below,

        ```javascript
        getDataFromHttp()
          .then(function (result) {
            return processDataAsync(result);
          })
          .done(function (processed) {
            displayData(processed);
          });
        ```

        In future, if the processing library API changed to synchronous then you can remove `done` block as below,

        ```javascript
        getDataFromHttp().then(function (result) {
          return displayData(processDataAsync(result));
        });
        ```

        and then you forgot to add `done` block to `then` block leads to silent errors.

     3. **Extend ES6 Promises by Bluebird:**
        Bluebird extends the ES6 Promises API to avoid the issue in the second solution. This library has a “default” onRejection handler which will print all errors from rejected Promises to stderr. After installation, you can process unhandled rejections

        ```javascript
        Promise.onPossiblyUnhandledRejection(function (error) {
          throw error;
        });
        ```

        and discard a rejection, just handle it with an empty catch

        ```javascript
        Promise.reject("error value").catch(function () {});
        ```

     **[⬆ Back to Top](#table-of-contents)**

409. ### What is deno

     Deno is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 JavaScript engine and the Rust programming language.

     **[⬆ Back to Top](#table-of-contents)**

410. ### How do you make an object iterable in javascript

     By default, plain objects are not iterable. But you can make the object iterable by defining a `Symbol.iterator` property on it.

     Let's demonstrate this with an example,

     ```javascript
     const collection = {
       one: 1,
       two: 2,
       three: 3,
       [Symbol.iterator]() {
         const values = Object.keys(this);
         let i = 0;
         return {
           next: () => {
             return {
               value: this[values[i++]],
               done: i > values.length,
             };
           },
         };
       },
     };

     const iterator = collection[Symbol.iterator]();

     console.log(iterator.next()); // → {value: 1, done: false}
     console.log(iterator.next()); // → {value: 2, done: false}
     console.log(iterator.next()); // → {value: 3, done: false}
     console.log(iterator.next()); // → {value: undefined, done: true}
     ```

     The above process can be simplified using a generator function,

     ```javascript
     const collection = {
       one: 1,
       two: 2,
       three: 3,
       [Symbol.iterator]: function* () {
         for (let key in this) {
           yield this[key];
         }
       },
     };
     const iterator = collection[Symbol.iterator]();
     console.log(iterator.next()); // {value: 1, done: false}
     console.log(iterator.next()); // {value: 2, done: false}
     console.log(iterator.next()); // {value: 3, done: false}
     console.log(iterator.next()); // {value: undefined, done: true}
     ```

     **[⬆ Back to Top](#table-of-contents)**

411. ### What is a Proper Tail Call

     First, we should know about tail call before talking about "Proper Tail Call". A tail call is a subroutine or function call performed as the final action of a calling function. Whereas **Proper tail call(PTC)** is a technique where the program or code will not create additional stack frames for a recursion when the function call is a tail call.

     For example, the below classic or head recursion of factorial function relies on stack for each step. Each step need to be processed upto `n * factorial(n - 1)`

     ```javascript
     function factorial(n) {
       if (n === 0) {
         return 1;
       }
       return n * factorial(n - 1);
     }
     console.log(factorial(5)); //120
     ```

     But if you use Tail recursion functions, they keep passing all the necessary data it needs down the recursion without relying on the stack.

     ```javascript
     function factorial(n, acc = 1) {
       if (n === 0) {
         return acc;
       }
       return factorial(n - 1, n * acc);
     }
     console.log(factorial(5)); //120
     ```

     The above pattern returns the same output as the first one. But the accumulator keeps track of total as an argument without using stack memory on recursive calls.

     **[⬆ Back to Top](#table-of-contents)**

412. ### How do you check an object is a promise or not

     If you don't know if a value is a promise or not, wrapping the value as `Promise.resolve(value)` which returns a promise

     ```javascript
     function isPromise(object) {
       if (Promise && Promise.resolve) {
         return Promise.resolve(object) == object;
       } else {
         throw "Promise not supported in your environment";
       }
     }

     var i = 1;
     var promise = new Promise(function (resolve, reject) {
       resolve();
     });

     console.log(isPromise(i)); // false
     console.log(isPromise(promise)); // true
     ```

     Another way is to check for `.then()` handler type

     ```javascript
     function isPromise(value) {
       return Boolean(value && typeof value.then === "function");
     }
     var i = 1;
     var promise = new Promise(function (resolve, reject) {
       resolve();
     });

     console.log(isPromise(i)); // false
     console.log(isPromise(promise)); // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

413. ### How to detect if a function is called as constructor

     You can use `new.target` pseudo-property to detect whether a function was called as a constructor(using the new operator) or as a regular function call.

     1. If a constructor or function invoked using the new operator, new.target returns a reference to the constructor or function.
     2. For function calls, new.target is undefined.

     ```javascript
     function Myfunc() {
       if (new.target) {
         console.log("called with new");
       } else {
         console.log("not called with new");
       }
     }

     new Myfunc(); // called with new
     Myfunc(); // not called with new
     Myfunc.call({}); // not called with new
     ```

     **[⬆ Back to Top](#table-of-contents)**

414. ### What are the differences between arguments object and rest parameter

     There are three main differences between arguments object and rest parameters

     1. The arguments object is an array-like but not an array. Whereas the rest parameters are array instances.
     2. The arguments object does not support methods such as sort, map, forEach, or pop. Whereas these methods can be used in rest parameters.
     3. The rest parameters are only the ones that haven’t been given a separate name, while the arguments object contains all arguments passed to the function

     **[⬆ Back to Top](#table-of-contents)**

415. ### What are the differences between spread operator and rest parameter

     Rest parameter collects all remaining elements into an array. Whereas Spread operator allows iterables( arrays / objects / strings ) to be expanded into single arguments/elements. i.e, Rest parameter is opposite to the spread operator.

     **[⬆ Back to Top](#table-of-contents)**

416. ### What are the different kinds of generators

     There are five kinds of generators,

     1. **Generator function declaration:**

        ```javascript
        function* myGenFunc() {
          yield 1;
          yield 2;
          yield 3;
        }
        const genObj = myGenFunc();
        ```

     2. **Generator function expressions:**

        ```javascript
        const myGenFunc = function* () {
          yield 1;
          yield 2;
          yield 3;
        };
        const genObj = myGenFunc();
        ```

     3. **Generator method definitions in object literals:**

        ```javascript
        const myObj = {
          *myGeneratorMethod() {
            yield 1;
            yield 2;
            yield 3;
          },
        };
        const genObj = myObj.myGeneratorMethod();
        ```

     4. **Generator method definitions in class:**

        ```javascript
        class MyClass {
          *myGeneratorMethod() {
            yield 1;
            yield 2;
            yield 3;
          }
        }
        const myObject = new MyClass();
        const genObj = myObject.myGeneratorMethod();
        ```

     5. **Generator as a computed property:**

        ```javascript
        const SomeObj = {
          *[Symbol.iterator]() {
            yield 1;
            yield 2;
            yield 3;
          },
        };

        console.log(Array.from(SomeObj)); // [ 1, 2, 3 ]
        ```

     **[⬆ Back to Top](#table-of-contents)**

417. ### What are the built-in iterables

     Below are the list of built-in iterables in javascript,

     1. Arrays and TypedArrays
     2. Strings: Iterate over each character or Unicode code-points
     3. Maps: iterate over its key-value pairs
     4. Sets: iterates over their elements
     5. arguments: An array-like special variable in functions
     6. DOM collection such as NodeList

     **[⬆ Back to Top](#table-of-contents)**

418. ### What are the differences between for...of and for...in statements

     Both for...in and for...of statements iterate over js data structures. The only difference is over what they iterate:

     1. for..in iterates over all enumerable property keys of an object
     2. for..of iterates over the values of an iterable object.

     Let's explain this difference with an example,

     ```javascript
     let arr = ["a", "b", "c"];

     arr.newProp = "newVlue";

     // key are the property keys
     for (let key in arr) {
       console.log(key); // 0, 1, 2 & newValue
     }

     // value are the property values
     for (let value of arr) {
       console.log(value); // a, b, c
     }
     ```

     Since for..in loop iterates over the keys of the object, the first loop logs 0, 1, 2 and newProp while iterating over the array object. The for..of loop iterates over the values of a arr data structure and logs a, b, c in the console.

     **[⬆ Back to Top](#table-of-contents)**

419. ### How do you define instance and non-instance properties

     The Instance properties must be defined inside of class methods. For example, name and age properties defined inside constructor as below,

     ```javascript
     class Person {
       constructor(name, age) {
         this.name = name;
         this.age = age;
       }
     }
     ```

     But Static(class) and prototype data properties must be defined outside of the ClassBody declaration. Let's assign the age value for Person class as below,

     ```javascript
     Person.staticAge = 30;
     Person.prototype.prototypeAge = 40;
     ```

     **[⬆ Back to Top](#table-of-contents)**

420. ### What is the difference between isNaN and Number.isNaN?

     1. **isNaN**: The global function `isNaN` converts the argument to a Number and returns true if the resulting value is NaN.
     2. **Number.isNaN**: This method does not convert the argument. But it returns true when the type is a Number and value is NaN.

     Let's see the difference with an example,

     ```javascript
     isNaN(‘hello’);   // true
     Number.isNaN('hello'); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

421. ### How to invoke an IIFE without any extra brackets?

     Immediately Invoked Function Expressions(IIFE) requires a pair of parenthesis to wrap the function which contains set of statements.

     ```js
     (function (dt) {
       console.log(dt.toLocaleTimeString());
     })(new Date());
     ```

     Since both IIFE and void operator discard the result of an expression, you can avoid the extra brackets using `void operator` for IIFE as below,

     ```js
     void (function (dt) {
       console.log(dt.toLocaleTimeString());
     })(new Date());
     ```

     **[⬆ Back to Top](#table-of-contents)**

422. ### Is that possible to use expressions in switch cases?

     You might have seen expressions used in switch condition but it is also possible to use for switch cases by assigning true value for the switch condition. Let's see the weather condition based on temparature as an example,

     ```js
     const weather = (function getWeather(temp) {
       switch (true) {
         case temp < 0:
           return "freezing";
         case temp < 10:
           return "cold";
         case temp < 24:
           return "cool";
         default:
           return "unknown";
       }
     })(10);
     ```

     **[⬆ Back to Top](#table-of-contents)**

423. ### What is the easiest way to ignore promise errors?

     The easiest and safest way to ignore promise errors is void that error. This approach is ESLint friendly too.

     ```js
     await promise.catch((e) => void e);
     ```

     **[⬆ Back to Top](#table-of-contents)**

424. ### How do style the console output using CSS?

     You can add CSS styling to the console output using the CSS format content specifier %c. The console string message can be appended after the specifier and CSS style in another argument. Let's print the red the color text using console.log and CSS specifier as below,

     ```js
     console.log("%cThis is a red text", "color:red");
     ```

     It is also possible to add more styles for the content. For example, the font-size can be modified for the above text

     ```js
     console.log(
       "%cThis is a red text with bigger font",
       "color:red; font-size:20px"
     );
     ```

     **[⬆ Back to Top](#table-of-contents)**

425. ### What is nullish coalescing operator (??)?

     It is a logical operator that returns its right-hand side operand when its left-hand side operand is null or undefined, and otherwise returns its left-hand side operand. This can be contrasted with the logical OR (||) operator, which returns the right-hand side operand if the left operand is any falsy value, not only null or undefined.

     ```js
     console.log(null ?? true); // true
     console.log(false ?? true); // false
     console.log(undefined ?? true); // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

426. ### How do you group and nest console output?

     The `console.group()` can be used to group related log messages to be able to easily read the logs and use console.groupEnd()to close the group. Along with this, you can also nest groups which allows to output message in hierarchical manner.

     For example, if you’re logging a user’s details:

     ```js
     console.group("User Details");
     console.log("name: Sudheer Jonna");
     console.log("job: Software Developer");

     // Nested Group
     console.group("Address");
     console.log("Street: Commonwealth");
     console.log("City: Los Angeles");
     console.log("State: California");

     // Close nested group
     console.groupEnd();

     // Close outer group
     console.groupEnd();
     ```

     You can also use `console.groupCollapsed()` instead of `console.group()` if you want the groups to be collapsed by default.

     **[⬆ Back to Top](#table-of-contents)**

427. ### What is the difference between dense and sparse arrays?

     An array contains items at each index starting from first(0) to last(array.length - 1) is called as Dense array. Whereas if at least one item is missing at any index, the array is called as sparse.

     Let's see the below two kind of arrays,

     ```js
     const avengers = ["Ironman", "Hulk", "CaptainAmerica"];
     console.log(avengers[0]); // 'Ironman'
     console.log(avengers[1]); // 'Hulk'
     console.log(avengers[2]); // 'CaptainAmerica'
     console.log(avengers.length); // 3

     const justiceLeague = ["Superman", "Aquaman", , "Batman"];
     console.log(justiceLeague[0]); // 'Superman'
     console.log(justiceLeague[1]); // 'Aquaman'
     console.log(justiceLeague[2]); // undefined
     console.log(justiceLeague[3]); // 'Batman'
     console.log(justiceLeague.length); // 4
     ```

     **[⬆ Back to Top](#table-of-contents)**

428. ### What are the different ways to create sparse arrays?

     There are 4 different ways to create sparse arrays in JavaScript

     1. **Array literal:** Omit a value when using the array literal
        ```js
        const justiceLeague = ["Superman", "Aquaman", , "Batman"];
        console.log(justiceLeague); // ['Superman', 'Aquaman', empty ,'Batman']
        ```
     2. **Array() constructor:** Invoking Array(length) or new Array(length)
        ```js
        const array = Array(3);
        console.log(array); // [empty, empty ,empty]
        ```
     3. **Delete operator:** Using delete array[index] operator on the array
        ```js
        const justiceLeague = ["Superman", "Aquaman", "Batman"];
        delete justiceLeague[1];
        console.log(justiceLeague); // ['Superman', empty, ,'Batman']
        ```
     4. **Increase length property:** Increasing length property of an array
        ```js
        const justiceLeague = ["Superman", "Aquaman", "Batman"];
        justiceLeague.length = 5;
        console.log(justiceLeague); // ['Superman', 'Aquaman', 'Batman', empty, empty]
        ```

     **[⬆ Back to Top](#table-of-contents)**

429. ### What is the difference between setTimeout, setImmediate and process.nextTick?

     1. **Set Timeout:** setTimeout() is to schedule execution of a one-time callback after delay milliseconds.
     2. **Set Immediate:** The setImmediate function is used to execute a function right after the current event loop finishes.
     3. **Process NextTick:** If process.nextTick() is called in a given phase, all the callbacks passed to process.nextTick() will be resolved before the event loop continues. This will block the event loop and create I/O Starvation if process.nextTick() is called recursively.

     **[⬆ Back to Top](#table-of-contents)**

430. ### How do you reverse an array without modifying original array?

     The `reverse()` method reverses the order of the elements in an array but it mutates the original array. Let's take a simple example to demonistrate this case,

     ```javascript
     const originalArray = [1, 2, 3, 4, 5];
     const newArray = originalArray.reverse();

     console.log(newArray); // [ 5, 4, 3, 2, 1]
     console.log(originalArray); // [ 5, 4, 3, 2, 1]
     ```

     There are few solutions that won't mutate the original array. Let's take a look.

     1. **Using slice and reverse methods:**
        In this case, just invoke the `slice()` method on the array to create a shallow copy followed by `reverse()` method call on the copy.

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.slice().reverse(); //Slice an array gives a new copy

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     2. **Using spread and reverse methods:**
        In this case, let's use the spread syntax (...) to create a copy of the array followed by `reverse()` method call on the copy.

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = [...originalArray].reverse();

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     3. **Using reduce and spread methods:**
        Here execute a reducer function on an array elements and append the accumulated array on right side using spread syntax

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduce((accumulator, value) => {
          return [value, ...accumulator];
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     4. **Using reduceRight and spread methods:**
        Here execute a right reducer function(i.e. opposite direction of reduce method) on an array elements and append the accumulated array on left side using spread syntax

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduceRight((accumulator, value) => {
          return [...accumulator, value];
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     5. **Using reduceRight and push methods:**
        Here execute a right reducer function(i.e. opposite direction of reduce method) on an array elements and push the iterated value to the accumulator

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduceRight((accumulator, value) => {
          accumulator.push(value);
          return accumulator;
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     **[⬆ Back to Top](#table-of-contents)**

431. ### How do you create custom HTML element?

     The creation of custom HTML elements involves two main steps,

     1. **Define your custom HTML element:** First you need to define some custom class by extending HTMLElement class.
        After that define your component properties (styles,text etc) using `connectedCallback` method.
        **Note:** The browser exposes a function called `customElements.define` inorder to reuse the element.
        ```javascript
        class CustomElement extends HTMLElement {
          connectedCallback() {
            this.innerHTML = "This is a custom element";
          }
        }
        customElements.define("custom-element", CustomElement);
        ```
     2. **Use custome element just like other HTML element:** Declare your custom element as a HTML tag.

     ```javascript
        <body>
             <custom-element>
        </body>
     ```

     **[⬆ Back to Top](#table-of-contents)**

432. ### What is global execution context?

     The global execution context is the default or first execution context that is created by the JavaScript engine before any code is executed(i.e, when the file first loads in the browser). All the global code that is not inside a function or object will be executed inside this global execution context. Since JS engine is single threaded there will be only one global environment and there will be only one global execution context.

     For example, the below code other than code inside any function or object is executed inside the global execution context.

     ```javascript
     var x = 10;

     function A() {
       console.log("Start function A");

       function B() {
         console.log("In function B");
       }

       B();
     }

     A();

     console.log("GlobalContext");
     ```

     **[⬆ Back to Top](#table-of-contents)**

433. ### What is function execution context?

     Whenever a function is invoked, the JavaScript engine creates a different type of Execution Context known as a Function Execution Context (FEC) within the Global Execution Context (GEC) to evaluate and execute the code within that function.

     **[⬆ Back to Top](#table-of-contents)**

434. ### What is debouncing?

     Debouncing is a programming pattern that allows delaying execution of some piece of code until a specified time to avoid unnecessary _CPU cycles, API calls and improve performance_. The debounce function make sure that your code is only triggered once per user input. The common usecases are Search box suggestions, text-field auto-saves, and eliminating double-button clicks.

     Let's say you want to show suggestions for a search query, but only after a visitor has finished typing it. So here you write a debounce function where the user keeps writing the characters with in 500ms then previous timer cleared out using `clearTimeout` and reschedule API call/DB query for a new time—300 ms in the future.

     ```js
     function debounce(func, timeout = 500) {
       let timer;
       return (...args) => {
         clearTimeout(timer);
         timer = setTimeout(() => {
           func.apply(this, args);
         }, timeout);
       };
     }
     function fetchResults() {
       console.log("Fetching input suggestions");
     }
     const processChange = debounce(() => fetchResults());
     ```

     The _debounce()_ function can be used on input, button and window events

     **Input:**

     ```html
     <input type="text" onkeyup="processChange()" />
     ```

     **Button:**

     ```html
     <button onclick="processChange()">Click me</button>
     ```

     **Windows event:**

     ```html
     window.addEventListener("scroll", processChange);
     ```

     **[⬆ Back to Top](#table-of-contents)**

435. ### What is throttling?

     Throttling is a technique used to limit the execution of an event handler function, even when this event triggers continuously due to user actions. The common use cases are browser resizing, window scrolling etc.

     The below example creates a throttle function to reduce the number of events for each pixel change and trigger scroll event for each 100ms except for the first event.

     ```js
     const throttle = (func, limit) => {
       let inThrottle;
       return (...args) => {
         if (!inThrottle) {
           func.apply(this, args);
           inThrottle = true;
           setTimeout(() => (inThrottle = false), limit);
         }
       };
     };
     window.addEventListener("scroll", () => {
       throttle(handleScrollAnimation, 100);
     });
     ```

     **[⬆ Back to Top](#table-of-contents)**

436. ### What is optional chaining?

     According to MDN official docs, the optional chaining operator (?.) permits reading the value of a property located deep within a chain of connected objects without having to expressly validate that each reference in the chain is valid.

     The ?. operator is like the . chaining operator, except that instead of causing an error if a reference is nullish (null or undefined), the expression short-circuits with a return value of undefined. When used with function calls, it returns undefined if the given function does not exist.

     ```js
     const adventurer = {
       name: "Alice",
       cat: {
         name: "Dinah",
       },
     };

     const dogName = adventurer.dog?.name;
     console.log(dogName);
     // expected output: undefined

     console.log(adventurer.someNonExistentMethod?.());
     // expected output: undefined
     ```

     **[⬆ Back to Top](#table-of-contents)**

437. ### What is an environment record?

     According to ECMAScript specification 262 (9.1):

     > [Environment Record](https://262.ecma-international.org/12.0/#sec-environment-records) is a specification type used to define the association of Identifiers to specific variables and functions, based upon the lexical nesting structure of ECMAScript code.

     Usually an Environment Record is associated with some specific syntactic structure of ECMAScript code such as a FunctionDeclaration, a BlockStatement, or a Catch clause of a TryStatement.

     Each time such code is evaluated, a new Environment Record is created to record the identifier bindings that are created by that code.

     **[⬆ Back to Top](#table-of-contents)**

438. ### How to verify if a variable is an array?

     It is possible to check if a variable is an array instance using 3 different ways,

     1. Array.isArray() method:

        The `Array.isArray(value)` utility function is used to determine whether value is an array or not. This function returns a true boolean value if the variable is an array and a false value if it is not.

        ```javascript
        const numbers = [1, 2, 3];
        const user = { name: "John" };
        Array.isArray(numbers); // true
        Array.isArray(user); //false
        ```

     2. instanceof operator:

        The instanceof operator is used to check the type of an array at run time. It returns true if the type of a variable is an Array other false for other type.

        ```javascript
        const numbers = [1, 2, 3];
        const user = { name: "John" };
        console.log(numbers instanceof Array); // true
        console.log(user instanceof Array); // false
        ```

     3. Checking constructor type:

        The constructor property of the variable is used to determine whether the variable Array type or not.

        ```javascript
        const numbers = [1, 2, 3];
        const user = { name: "John" };
        console.log(numbers.constructor === Array); // true
        console.log(user.constructor === Array); // false
        ```

     **[⬆ Back to Top](#table-of-contents)**

439. ### What is pass by value and pass by reference?

     Pass-by-value creates a new space in memory and makes a copy of a value. Primitives such as string, number, boolean etc will actually create a new copy. Hence, updating one value doesn't impact the other value. i.e, The values are independent of each other.

     ```javascript
     let a = 5;
     let b = a;

     b++;
     console.log(a, b); //5, 6
     ```

     In the above code snippet, the value of `a` is assigned to `b` and the variable `b` has been incremented. Since there is a new space created for variable `b`, any update on this variable doesn't impact the variable `a`.

     Pass by reference doesn't create a new space in memory but the new variable adopts a memory address of an initial variable. Non-primitives such as objects, arrays and functions gets the reference of the initiable variable. i.e, updating one value will impact the other variable.

     ```javascript
     let user1 = {
       name: "John",
       age: 27,
     };
     let user2 = user1;
     user2.age = 30;

     console.log(user1.age, user2.age); // 30, 30
     ```

     In the above code snippet, updating the `age` property of one object will impact the other property due to the same reference.

     **[⬆ Back to Top](#table-of-contents)**

440. ### What are the differences between primitives and non-primitives?

     JavaScript language has both primitives and non-primitives but there are few differences between them as below,

     | Primitives                 | Non-primitives       |
     | -------------------------- | -------------------- |
     | These types are predefined | Created by developer |
     | These are immutable        | Mutable              |
     | Compare by value           | Compare by reference |
     | Stored in Stack            | Stored in heap       |
     | Contain certain value      | Can contain NULL too |

     **[⬆ Back to Top](#table-of-contents)**

441. ### How do you create your own bind method using either call or apply method?

     The custom bind function needs to be created on Function prototype inorder to use it as other builtin functions. This custom function should return a function similar to original bind method and the implementation of inner function needs to use apply method call.

     The function which is going to bind using custom `myOwnBind` method act as the attached function(`boundTargetFunction`) and argument as the object for `apply` method call.

     ```js
     Function.prototype.myOwnBind = function (whoIsCallingMe) {
       if (typeof this !== "function") {
         throw new Error(this + "cannot be bound as it's not callable");
       }
       const boundTargetFunction = this;
       return function () {
         boundTargetFunction.apply(whoIsCallingMe, arguments);
       };
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

442. ### What are the differences between pure and impure functions?

     Some of the major differences between pure and impure function are as below,

| Pure function                       | Impure function                                                       |
| ----------------------------------- | --------------------------------------------------------------------- |
| It has no side effects              | It causes side effects                                                |
| It is always return the same result | It returns different result on each call                              |
| Easy to read and debug              | Difficult to read and debug because they are affected by extenal code |

**[⬆ Back to Top](#table-of-contents)**

445. ### What is referential transparency?

An expression in javascript that can be replaced by its value without affecting the behaviour of the program is called referential transparency. Pure functions are referentially transparent.

```javascript
const add = (x, y) => x + y;
const multiplyBy2 = (x) => x * 2;

//Now add (2, 3) can be replaced by 5.

multiplyBy2(add(2, 3));
```

**[⬆ Back to Top](#table-of-contents)**

446. ### What are the possible side-effects in javascript?

     A side effect is the modification of the state through the invocation of a function or expression. These side effects make our function impure by default. Below are some side effects which make function impure,

- Making an HTTP request. Asynchronous functions such as fetch and promise are impure.
- DOM manipulations
- Mutating the input data
- Printing to a screen or console: For example, console.log() and alert()
- Fetching the current time
- Math.random() calls: Modifies the internal state of Math object

**[⬆ Back to Top](#table-of-contents)**

447. ### What are compose and pipe functions?

     The "compose" and "pipe" are two techniques commonly used in functional programming to simplify complex operations and make code more readable. They are not native to JavaScript and higher-order functions. the `compose()` applies right to left any number of functions to the output of the previous function.

     **[⬆ Back to Top](#table-of-contents)**

448. ### What is module pattern?

     Module pattern is a designed pattern used to wrap a set of variables and functions together in a single scope returned as an object. JavaScript doesn't have access specifiers similar to other languages(Java, Python, etc) to provide private scope. It uses IIFE (Immediately invoked function expression) to allow for private scopes. i.e., a closure that protect variables and methods.

     The module pattern looks like below,

     ```javascript
     (function () {
       // Private variables or functions goes here.

       return {
         // Return public variables or functions here.
       };
     })();
     ```

     Let's see an example of a module pattern for an employee with private and public access,

     ```javascript
     const createEmployee = (function () {
       // Private
       const name = "John";
       const department = "Sales";
       const getEmployeeName = () => name;
       const getDepartmentName = () => department;

       // Public
       return {
         name,
         department,
         getName: () => getEmployeeName(),
         getDepartment: () => getDepartmentName(),
       };
     })();

     console.log(createEmployee.name);
     console.log(createEmployee.department);
     console.log(createEmployee.getName());
     console.log(createEmployee.getDepartment());
     ```

     **Note:** It mimic the concepts of classes with private variables and methods.

     **[⬆ Back to Top](#table-of-contents)**

449. ### What is Function Composition?

     It is an approach where the result of one function is passed on to the next function, which is passed to another until the final function is executed for the final result.

     ```javascript
     //example
     const double = (x) => x * 2;
     const square = (x) => x * x;

     var output1 = double(2);
     var output2 = square(output1);
     console.log(output2);

     var output_final = square(double(2));
     console.log(output_final);
     ```

     **[⬆ Back to Top](#table-of-contents)**

450. ### How to use await outside of async function prior to ES2022?

     Prior to ES2022, if you attempted to use an await outside of an async function resulted in a SyntaxError.

     ```javascript
     await Promise.resolve(console.log("Hello await")); // SyntaxError: await is only valid in async function
     ```

     But you can fix this issue with an alternative IIFE (Immediately Invoked Function Expression) to get access to the feature.

     ```javascript
     (async function () {
       await Promise.resolve(console.log("Hello await")); // Hello await
     })();
     ```

     In ES2022, you can write top-level await without writing any hacks.

     ```javascript
     await Promise.resolve(console.log("Hello await")); //Hello await
     ```

**[⬆ Back to Top](#table-of-contents)**


## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊
