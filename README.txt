
This version of sqoop has support for beeline hacked into it. New paramaters have been added to allow the user to specify the JDBC connection string, username, and password to pass to beeline. This was put toghther in a bit of a rush but it works.

The following aditional paramaters have been added to the commandline
--beeline-connection-string 
--beeline-user
--beeline-password
--beeline-password-file

!!!!!!Anything below this point is the normal readme!!!!!!

= Welcome to Sqoop!

This is the Sqoop (SQL-to-Hadoop) tool. Sqoop allows easy imports and
exports of data sets between databases and HDFS.


== More Documentation

Sqoop ships with additional documentation: a user guide and a manual page.

Asciidoc sources for both of these are in +src/docs/+. Run +ant docs+ to build
the documentation. It will be created in +build/docs/+.

If you got Sqoop in release form, documentation will already be built and
available in the +docs/+ directory.


== Compiling Sqoop

Compiling Sqoop requires the following tools:

* Apache ant (1.7.1)
* Java JDK 1.6

Additionally, building the documentation requires these tools:

* asciidoc
* make
* python 2.5+
* xmlto
* tar
* gzip

To compile Sqoop, run +ant package+. There will be a fully self-hosted build
provided in the +build/sqoop-(version)/+ directory. 

You can build just the jar by running +ant jar+.

See the COMPILING.txt document for for information.

== This is also an Asciidoc file!

* Try running +asciidoc README.txt+
* For more information about asciidoc, see http://www.methods.co.nz/asciidoc/

