# homebrew-sbt

**Archived as this is [now fixed upstream](https://github.com/Homebrew/homebrew-core/commit/ead23d60cf3d06cc621e65e19228a12add5d1fd8#diff-fa60f13055f7e52179d5d587a5461c16f88750366ba22a2c46023d8b6599374e).**

Modified [Homebrew] tap for [`sbt`] which installs on M1 (arm64) machines.

At time of writing (2021-10-01) the current `sbt` formula does not install
due to it including a non-arm64 binary: `sbtn` which requires x86_64.
See [Homebrew/homebrew-core#76947](https://github.com/Homebrew/homebrew-core/pull/76947)
for more details.

Usage:
  
	$ brew tap bastewart/sbt
	$ brew install bastewart/sbt/sbt

[Homebrew]: https://brew.sh/
[`sbt`]: (https://www.scala-sbt.org/)
