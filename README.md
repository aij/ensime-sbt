# ENSIME-sbt-cmd 
An sbt plugin that supports integration with the ENSIME IDE.


# Versions

__For use with ensime 0.9.0+__
0.7.0-SNAPSHOT


## how to setup
Add the following to your `~/.sbt/plugins/build.sbt`:

    resolvers += "Scala-Tools Maven2 Snapshots Repository" at "http://scala-tools.org/repo-snapshots"

    addSbtPlugin("org.ensime" % "ensime-sbt-cmd" % "VERSION")

## how to use
The above automatically adds the `ensime generate` command to your sbt build. This command will write a .ensime file to your project's root directory.

## License
BSD License
