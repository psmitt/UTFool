# The UTFool Programming Language

UTFool /pron. as ~~b~~eautiful/ is a Unicode-based object-oriented
programming language designed for trans-compilation to any other
object-oriented source (e.g. Java, JavaScript or Python).

UTFool is highly flexible on the lexical level.
_Keywords_, _delimiters_ and _operators_ are replaceable
by any unique sequence of symbols.
Besides of the usual forms of _comments_,
the UTFool source can contain _expletives_ and _aliases_
in order to increase readability.
UTFool does support language-specific solutions as well,
by allowing _embedded code_ fragments from the target language.

Defining your own vocabulary,
you can design your own programming dialect with UTFool.
In order to easily understand other sources,
you can translate them to your dialect.
Developer teams can use their common dialect, as a coding convention.
With UTFool you can be concise or eloquent, according to your style.

## Formal Grammar

* [UTFool Lexical Structure](https://rawgit.com/psmitt/metalanguage/master/examples/UTFool%20Lexical%20Structure.xml)
* [UTFool Syntactic Grammar](https://rawgit.com/psmitt/metalanguage/master/examples/UTFool%20Syntactic%20Grammar.xml)

Notice the moderate vocabulary of the grammar.
The aim is to give you the widest room for creating your own terms.
You can define several aliases for the same keyword in order to
increase the expressiveness of your code.
You can even override a keyword and make it free to use as a name,
if you intend to trans-compile your script to a language
where this name is used for a function or class.
Instead of `iterate` you can write e.g.
`repeat`, `loop`, `for`, `🔁` or `∀` within the very same project.

## Flexible Binary Operator Precedence

Have you even wondered why bitwise operators have lower precedence
than relational operators, or why bit-shift is weaker than addition?
This heritage from C can be overridden now in UTFool.
UTFool offers you the freedom to arbitrarily redefine the precedence
of binary operators.

An example of a reasonable new order:

<table>
<tr>
<td>

#### I. Unary operators
#### II. Binary operators

1. bitwise operators
   * shifts and rotations
   * and, or, xor
2. arithmetic operators
   * exponentiation
   * multiplicative operators
   * additive operators
3. string operators
   * concatenation
4. list operators
   * list separator
5. relational operators ( chaining is supported )
6. logical operators
   * and, or, xor
   * nand, nor
7. coalescing operators
   * first-non-false
   * first-non-null

#### III. Ternary operator
</td>
<td>
/ a sample from the operator precedence file /
<img src="https://raw.githubusercontent.com/psmitt/UTFool/master/operators.png"/>
</td>
</table>

## Code edition, code samples

UTFool source code gets created in a UTF-8 encoded text file.
Due to the extended usage of the Unicode character set,
it is advisable to setup a font with great coverage of the Basic
or even the Supplementary Multilingual Plane.
[GNU FreeMono](https://www.gnu.org/software/freefont) is a good choice.

Beyond of the font selection, another common need is
the easy typing of the different Unicode symbols on any keyboard.
[AutoHotkey](https://autohotkey.com) offers the simplest solution
by smart macros and handy shortcuts, making you able to insert any
Unicode sequence on a keystroke or two.

Regarding the text editors you find a wide selection on the web.
You can use [Atom](https://atom.io) on any platform, or the lightweight
[Notepad2](https://xhmikosr.github.io/notepad2-mod) on Windows.
They both provide you the aesthetic appearance of UTFool sources.
Have a taste of it here, and see more on
[RosettaCode.org](http://rosettacode.org/wiki/UTFool):

![](https://raw.githubusercontent.com/psmitt/UTFool/master/sample.png)

## UTFool Compiler to Java

Coming soon...
