## Install

Installing fsharp is pretty simple now. just run `sudo apt-get update && sudo apt-get install fsharp`. You should now have a couple command line apps `fsharpc` and `fsharpi`. `fsharpi` is the F# Repl. `fsharpc` is the F# compiler.

### ASP.NET MVC4

In order to actually run a test webserver you will also need to install `mono-xsp4`. Run `sudo apt-get update && sudo apt-get install mono-csp4 asp.net-examples`.

## Recommended IDE

While you're free to edit `.fs` files with any text editor Mono Develop is a great full featured IDE. If you're used to tools like Visual Studio you'll definitely want to install Mono Develop. To do so just run `sudo apt-get update && sudo apt-get install monodevelop`. Once Mono Develop is installed you will still need to install the F# bindings for Mono Develop. Click Tools > Add-in Manager to open the Add-in Manager. In the new add-in manager window click the Galler Tab, choose bindings, choose F# and click install.

### Additional Mono Develop Packages

#### Git & Subversion

`sudo apt-get install monodevelop-versioncontrol`

#### Nunit

`sudo apt-get install monodevelop-nunit`

#### Database Tools

For MySQL, SQLite, and PostgreSQL

`sudo apt-get install monodevelop-database`
