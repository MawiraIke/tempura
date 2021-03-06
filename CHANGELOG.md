> This project uses [Break Versioning](https://github.com/ptaoussanis/encore/blob/master/BREAK-VERSIONING.md)

## v1.2.1 - 2018 Apr 15

```clojure
[com.taoensso/tempura "1.2.1"]
```

> This is a non-breaking hotfix release.

* [#21] **Fix**: edge-case preventing blank `:missing` vals (@kaosko)

## v1.2.0 - 2018 Mar 11

```clojure
[com.taoensso/tempura "1.2.0"]
```

> This is a non-breaking maintenance release.

* [#20] Fix: bug with arg-only resources (@DjebbZ)
* **Impl**: Bump dependencies, incl. ClojureScript

## v1.1.2 - 2017 Mar 28

```clojure
[com.taoensso/tempura "1.1.2"]
```

> This is a non-breaking hotfix release.

* [#9] **Fix**: Typo was breaking :missing-resource-fn (@brjann)

## v1.1.1 - 2017 Feb 18

```clojure
[com.taoensso/tempura "1.1.1"]
```

* **Fix**: broken unit tests

## v1.1.0 - 2017 Feb 16

```clojure
[com.taoensso/tempura "1.1.0"]
```

* **BREAKING**: Throw on missing `:__load-resource` files (used to fail silently)
* [#5] **New**: Added experimental utils: `load-resource-at-runtime`, `load-resource-at-compile-time`
* **Impl**: Normalize locale casing: `:en-GB` <=> `:en-gb`

## v1.0.0 - 2016 Dec 17

```clojure
[com.taoensso/tempura "1.0.0"]
```

> Non-breaking v1.0.0 release.

* **Fix**: [#4] `tr` doc-string typo

## v1.0.0-RC4 - 2016 Nov 13

```clojure
[com.taoensso/tempura "1.0.0-RC4"]
```

* **BREAKING**: Ring middleware: use namespaced keys.
* [#3] **New**: Make `parse-http-accept-header` public (@yogthos).


## v1.0.0-RC3 - 2016 Oct 17

```clojure
[com.taoensso/tempura "1.0.0-RC3"]
```

> Initial public release. Sorry for taking so long to finally document+publish this!
