angular-toaster API for Scala.js
================================
[angular-toaster](https://www.npmjs.com/package/angularjs-toaster) - angular-toaster binding for Scala.js.

### Description

An `angular-toaster` binding for Scala.js.

### Build Dependencies

* [SBT v0.13.13](http://www.scala-sbt.org/download.html)

### Build/publish the SDK locally

```bash
 $ sbt clean publish-local
```

### Running the tests

Before running the tests the first time, you must ensure the npm packages are installed:

```bash
$ npm install
```

Then you can run the tests:

```bash
$ sbt test
```

### Artifacts and Resolvers

To add the `angular-toaster` binding to your project, add the following to your build.sbt:  

```sbt
libraryDependencies += "io.scalajs.npm" %%% "angular-toaster" % "2.1.0"
```

Optionally, you may add the Sonatype Repository resolver:

```sbt   
resolvers += Resolver.sonatypeRepo("releases") 
```