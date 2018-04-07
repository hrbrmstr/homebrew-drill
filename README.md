# Alternate Homebrew Tap for Apache Drill

There is a [Homebrew Core Formula](https://github.com/Homebrew/homebrew-core/blob/master/Formula/apache-drill.rb) for Apache Drill but it's out of date (1.10) and having a separate one will make it possible to provide custom formula for third party JARs and other Drill-things that will take too long to go into Homebrew Core.

My commits are also signed.

## Installing Apache Drill

    brew tap hrbrmstr/homebrew-drill
    brew install apache-drill

