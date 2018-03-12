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
The aim is to give you the widest room of creating your own terms.
You can define several aliases for the same keyword in order to
increase the expressiveness of your code.
You can even override a keyword and make it free to use as a name,
if you intend to trans-compile your code to a language
where this name is used for a function or class.
Instead of `iterate` you can write e.g.
`repeat`, `loop`, `for`, `🔁` or `∀` within the very same project.

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

With regards to the editor, there is a wide selection on the web.
You can use [Atom](https://atom.io) on any platform, or the lightweight
[Notepad2](https://xhmikosr.github.io/notepad2-mod) on Windows.
They both provide an aesthetic look for UTFool sources.
Have a taste of it:

<img alt="A screenshot of the 100 doors task solution" src="https://raw.githubusercontent.com/psmitt/UTFool/master/100_doors.png">

## UTFool Compiler to Java

Coming soon...
