# Dart Linux Package Repository
This is the Dart Linux Package Repository, built for @v1nch3ns0 's dart-linux repo!

## Main raw link to files is:
```https://raw.githubusercontent.com/Saveriokarol/dart-packages/[branch]/[filepath]```

## Repository Usage
1. Download ```manifest.css```
2. Parse after the first line in the order:

   | name       | version | filepath             | depends         | description                      |
   |------------|---------|----------------------|-----------------|----------------------------------|
   | curl       | 8.0.1   | network/curl.dartpkg | openssl,zlib    | Command line tool for transfers  |
   | nano       | 6.2     | editor/nano.dartpkg  | ncurses         | Simple terminal text editor      |
   | dart       | 3.3.0   | lang/dart.dartpkg    | libc,zlib       | Dart language SDK                |
   | git        | 2.43.0  | dev/git.dartpkg      | curl,openssl    | Distributed version control tool |
