Stylist
=======

Stylist teaches developers good programming and documentation style through a quiz where 
questions are automatically generated from prior projects.

 * Programming Languages:
   * Javascript (Google style guide)
 * Documentation:
   * Strunk and White's "The Elements of Style"

Javascript
----------

We use [JSCS](jscs.info) to lint code extracted from a user-submitted
Github repository following the Google style guide.


English Language Linting
------------------------

We use a [fork](https://github.com/feynmanliang/StrunkAndWhiteLinter) of
a [Strunk and White english
linter](https://github.com/deniseli/StrunkAndWhiteLinter) by @deniseli.
The rules which are checked include:

 * Context free:
    * Exclamations
    * In-word dashes
    * Parenthesis
    * First-person
 * Context dependent:
    * Singular possessive
    * As _or_ Then
    * As to Whether
    * Oxford comma
    * Date format
    * Omit needless words
    * Loose sentences

TODOs
-----

  [ ] Support style guides from other companies
  [ ] Support additional programming languages
  [ ] Implement more rules from Stark and White "The Elements of Style"
