# Dart Linux Package Repository
This is the Dart Linux Package Repository, built for @v1nch3ns0 's dart-linux repo!

## Main raw link to files is:
```https://raw.githubusercontent.com/Saveriokarol/dart-packages/[branch]/[filepath]```

## Repository Usage
1. Download ```manifest.csv```
2. Parse after the first line in the order (e.g.:)

   | name       | version | filepath           | depends         | description                      |
   |------------|---------|--------------------|-----------------|----------------------------------|
   | curl       | 8.0.1   | network/curl.dakg  | openssl,zlib    | Command line tool for transfers  |
   | nano       | 6.2     | editor/nano.dakg   | ncurses         | Simple terminal text editor      |
   | dart       | 3.3.0   | lang/dart.dakg     | libc,zlib       | Dart language SDK                |
   | git        | 2.43.0  | dev/git.dakg       | curl,openssl    | Distributed version control tool |
