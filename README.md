# homebrew-sbt

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
