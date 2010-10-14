# Specialised data types and languages

These types of data come up so frequently it's useful to know a little about them and the specialised languages that you use to work with them.

  * Strings and regular expressions
  * Databases and SQL
  * XML and XPath

# Advanced R topics

In the these topics I try and explain how fundamental R components work, taking the [R language definition][lang-def] and trying to make it more user friendly with plenty of examples to illustrate each idea.

  * [[The S3 object system|S3]]
  * [[Scoping, environments and closures|Scoping]]
  * [[Controlling evaluation|Evaluation]]
  * Lazy evaluation: default, delayedAssign, autoload, makeActiveBinding
  * Computing on the language: calls, expressions, functions

# Good development practices

The following documents give my opinionated beliefs on good development practice, distilled from my experience writing over 20 R packages.  You want to make sure that your code is:

  * correct (testing)
  * maintainable (style)
  * usable (good documentation)
  * easy to install (package)
  * available (git + github)
  * publicised

And you'll learn how to make it so in the following pages:

  * Package basics
  * Documentation
  * [[Introduction to namespaces|Namespaces]] for use with roxygen
  * Testing
  * Source code control: git + github
  * [[How to make a reproducible example|Reproducibility]]
  * [[A philosophy of data|data-philosophy]]
  * Style guide
  * Package release check list
  * Mastering the command line

  [lang-def]:http://cran.r-project.org/doc/manuals/R-lang.html
  