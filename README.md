# mozjpeg-rb
Simple script to optimize jpegs using mozjpeg

### Requirements

This requires the [mozjpeg](https://github.com/mozilla/mozjpeg) binaries in your path. On macOS you can just use `brew install mozjpeg`

### How to use

```shell
➜ chmod +x mozjpeg.rb
➜ ./mozjpeg.rb -all
➜ * skipped: test_01.jpg
➜ - saved: 0 KB
➜ * skipped: test_02.jpg
➜ - saved: 0 KB
➜ * optimized: test_03.jpg
➜ - saved: 9 KB
➜ * skipped: test_04.jpg
➜ - saved: 0 KB
➜ * skipped: test_05.jpg
➜ - saved: 0 KB
➜ * skipped: test_06.jpg
➜ - saved: 0 KB
➜ ** Total saved: 9 KB
```
