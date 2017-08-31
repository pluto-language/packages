# packages

The mapping of package names to source repositories.

In a &lt;package&gt;.yaml file, these are the valid fields. Any other fields are ignored.

field           | description                            | example
----------------|----------------------------------------|-----------------------------------
**title**       | The package's display name             | `"Maths"`
**description** | The package's description              | `"Some useful maths functions"`
**version**     | The package's version                  | `"0.1.4"`
**sources**     | A list of Pluto source files           | `["fns.pluto", "constants.pluto"]`
tags            | A list of tags relevant to the package | `["maths", "functions", "utility"]`
authors         | A list of authors of the package       | `["Zac Garby <me@zacgarby.co.uk>"]`
repository      | The repository where the code is held  | `"http://github.com/pluto-language/maths"`
homepage        | The homepage of the package            | `"http://pluto-maths-package.com"`
license         | The license the package uses           | `"MIT"`
