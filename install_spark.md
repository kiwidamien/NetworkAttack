# Installing spark
## Getting the right version of the Java JVM

1. Keep track of java versions:
```
brew install homebrew-cask
brew install jenv
brew install caskroom/versions
```
2. You can find all the versions that you would want to install with
```
brew cask search java
```
Here we want java8 (as of November 2017)
3. Install `java8` using
```
brew cask install java8
```
4. Change java environment
```
jenv add <javaVersionPath>
```
5. Change your `.bash_profile`:
```
export JAVA_HOME=$(/usr/libexec/java_home -v 1.8)
export PATH=$JAVA_HOME/bin:$PATH
```

## Install spark
1. If needed, install `xcode-select`
```
x-code select --install
```

2. Now install spark
```
brew install scala
brew install apache-spark
```
3. You might need to update your `.bash_profile` with Spark specific information:
```
export SPARK_HOME=/path/to/your/spark
export PATH="$SPARK_HOME/bin:$PATH"
export SPARK_LOCAL_IP="127.0.0.1"
```
