Chisel Project Template
=======================


#### Set project organization and name in build.sbt

The cleanup workflow will have attempted to provide sensible defaults for `ThisBuild / organization` and `name` in the `build.sbt`.
Feel free to use your text editor of choice to change them as you see fit.

#### Clean up the README.md file

Again, use you editor of choice to make the README specific to your project.

#### Add a LICENSE file

It is important to have a LICENSE for open source (or closed source) code.
This template repository has the Unlicense in order to allow users to add any license they want to derivative code.
The Unlicense is stripped when creating a repository from this template so that users do not accidentally unlicense their own work.

For more information about a license, check out the [Github Docs](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/adding-a-license-to-a-repository).

#### Commit your changes
```sh
git commit -m 'Starting learning_chisel'
git push origin main
```

### Did it work?

You should now have a working Chisel3 project.

You can run the included test with:
```sh
sbt test
```

You should see a whole bunch of output that ends with something like the following lines
```
[info] Tests: succeeded 1, failed 0, canceled 0, ignored 0, pending 0
[info] All tests passed.
[success] Total time: 5 s, completed Dec 16, 2020 12:18:44 PM
```
If you see the above then...

### It worked!

You are ready to go. We have a few recommended practices and things to do.

* Use packages and following conventions for [structure](https://www.scala-sbt.org/1.x/docs/Directories.html) and [naming](http://docs.scala-lang.org/style/naming-conventions.html)
* Package names should be clearly reflected in the testing hierarchy
* Build tests for all your work
* Read more about testing in SBT in the [SBT docs](https://www.scala-sbt.org/1.x/docs/Testing.html)
* This template includes a [test dependency](https://www.scala-sbt.org/1.x/docs/Library-Dependencies.html#Per-configuration+dependencies) on [chiseltest](https://github.com/ucb-bar/chisel-testers2), this is a reasonable starting point for most tests
  * You can remove this dependency in the build.sbt file if you want to
* Change the name of your project in the build.sbt file
* Change your README.md

## Problems? Questions?

Check out the [Chisel Users Community](https://www.chisel-lang.org/community.html) page for links to get in contact!
