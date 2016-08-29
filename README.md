# flush

Bash script to flush stuff, specifically DNS and Memcached.

This project is a port of my [Alfred Workflow][workflow]. I am moving away from
Alfred since most of what I using it for can be easily accomplished from the
command-line (where I already spend most of my time).

## Installation

Not yet... soon.

## Usage

```shell
flush [dns|memcached]
```

## Gotchas

The DNS flushing is very OS X specific right now but will be expanded to support
Linux soon enough. Memcached flushing requires the `nc` (or `netcat`) utility.

## Thanks

DNS flushing for OS X is based on Eugene Ventimiglia's [project][upstream]

[workflow]: https://github.com/joshtronic/alfred-workflow-flush
[upstream]: https://github.com/eventi/noreallyjustfuckingstopalready

