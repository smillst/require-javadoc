# Require-Javadoc change log

## 2.0.0 (2023-??-??)

Java 11 or later is required.

## 1.0.6 (2022-12-02)

Support JDK 19.

Don't transitively depend on commons-text 1.9, which is subject to CVE-2022-42889.

## 1.0.5 (2022-10-02)

`--dont-require-trivial-properties` supports unprefixed, record-style getters.

## 1.0.4 (2022-07-13)

Support new command-line options:
 * `--dont-require-noarg-constructor`
 * `--dont-require-trivial-properties`

## 1.0.3 (2022-01-25)

Support JDK 17.

## 1.0.2 (2021-04-30)

Reduced jar size.  No user-visible behavior changes.

## 1.0.1 (2020-12-18)

Warn about missing package documentation in file package-info.java.

Support new command-line options:
 * `--dont-require-private`
 * `--dont-require-type`
 * `--dont-require-field`
 * `--dont-require-method`
 * `--require-package-info`

Fix bug related to `//` comments before `@Override` annotation

## 1.0.0 (2020-09-01)

- Release 1.0.0.

## 0.3.1 (2020-08-08)

- Checks enums and annotations, which were ignored before.

## 0.3.0 (2020-04-09)

- require-javadoc is now a regular Java application, not a Javadoc doclet.
  Usage instructions have changed, and several limitations are removed.

## 0.1.3

- Add `--verbose` command-line argument, for debugging.

## 0.1.2 (2019-06-04)

- Reduce dependencies.

## 0.1.1

- Don't use Error Prone, which pulls in checker-qual 2.5.4.

## 0.1.0

- Update minor version number

## 0.0.9

- Don't warn about `values()` or `valueOf()` in enum classes.
