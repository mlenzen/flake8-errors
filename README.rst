==================================
 Compilation of all Flake8 Errors
==================================

.. csv-table:: Flake8 Errors
    :header: Section,Code,Example Message,Default,Source
    :widths: 8, 5, 20, 3, 5

    C9,C901,'function' is too complex (##),✔,pyflakes_
    Missing Docstrings,D100,Missing docstring in public module,✔,pydocstyle_
    Missing Docstrings,D101,Missing docstring in public class,✔,pydocstyle_
    Missing Docstrings,D102,Missing docstring in public method,✔,pydocstyle_
    Missing Docstrings,D103,Missing docstring in public function,✔,pydocstyle_
    Missing Docstrings,D104,Missing docstring in public package,✔,pydocstyle_
    Missing Docstrings,D105,Missing docstring in magic method,✔,pydocstyle_
    Missing Docstrings,D106,Missing docstring in public nested class,✔,pydocstyle_
    Missing Docstrings,D107,Missing docstring in __init__,✔,pydocstyle_
    Whitespace Issues,D200,One-line docstring should fit on one line with quotes,✔,pydocstyle_
    Whitespace Issues,D201,No blank lines allowed before function docstring,✔,pydocstyle_
    Whitespace Issues,D202,No blank lines allowed after function docstring,✔,pydocstyle_
    Whitespace Issues,D203,1 blank line required before class docstring,✔,pydocstyle_
    Whitespace Issues,D204,1 blank line required after class docstring,✔,pydocstyle_
    Whitespace Issues,D205,1 blank line required between summary line and description,✔,pydocstyle_
    Whitespace Issues,D206,"Docstring should be indented with spaces, not tabs",✔,pydocstyle_
    Whitespace Issues,D207,Docstring is under-indented,✔,pydocstyle_
    Whitespace Issues,D208,Docstring is over-indented,✔,pydocstyle_
    Whitespace Issues,D209,Multi-line docstring closing quotes should be on a separate line,✔,pydocstyle_
    Whitespace Issues,D210,No whitespaces allowed surrounding docstring text,✔,pydocstyle_
    Whitespace Issues,D211,No blank lines allowed before class docstring,✔,pydocstyle_
    Whitespace Issues,D212,Multi-line docstring summary should start at the first line,✔,pydocstyle_
    Whitespace Issues,D213,Multi-line docstring summary should start at the second line,✔,pydocstyle_
    Whitespace Issues,D214,Section is over-indented,✔,pydocstyle_
    Whitespace Issues,D215,Section underline is over-indented,✔,pydocstyle_
    Quotes Issues,D300,Use “”“triple double quotes”“”,✔,pydocstyle_
    Quotes Issues,D301,Use r”“” if any backslashes in a docstring,✔,pydocstyle_
    Quotes Issues,D302,Use u”“” for Unicode docstrings,✔,pydocstyle_
    Docstring Content Issues,D400,First line should end with a period,✔,pydocstyle_
    Docstring Content Issues,D401,First line should be in imperative mood,✔,pydocstyle_
    Docstring Content Issues,D401,First line should be in imperative mood; try rephrasing,✔,pydocstyle_
    Docstring Content Issues,D402,First line should not be the function`s “signature”,✔,pydocstyle_
    Docstring Content Issues,D403,First word of the first line should be properly capitalized,✔,pydocstyle_
    Docstring Content Issues,D404,First word of the docstring should not be This,✔,pydocstyle_
    Docstring Content Issues,D405,Section name should be properly capitalized,✔,pydocstyle_
    Docstring Content Issues,D406,Section name should end with a newline,✔,pydocstyle_
    Docstring Content Issues,D407,Missing dashed underline after section,✔,pydocstyle_
    Docstring Content Issues,D408,Section underline should be in the line following the section`s name,✔,pydocstyle_
    Docstring Content Issues,D409,Section underline should match the length of its name,✔,pydocstyle_
    Docstring Content Issues,D410,Missing blank line after section,✔,pydocstyle_
    Docstring Content Issues,D411,Missing blank line before section,✔,pydocstyle_
    Docstring Content Issues,D412,No blank lines allowed between a section header and its content,✔,pydocstyle_
    Docstring Content Issues,D413,Missing blank line after last section,✔,pydocstyle_
    Docstring Content Issues,D414,Section has no content,✔,pydocstyle_
    Docstring Content Issues,D415,"First line should end with a period, question mark, or exclamation point",✔,pydocstyle_
    Docstring Content Issues,D416,Section name should end with a colon,✔,pydocstyle_
    Docstring Content Issues,D417,Missing argument descriptions in the docstring,✔,pydocstyle_
    Indentation,E101,indentation contains mixed spaces and tabs,✔,pycodestyle_
    Indentation,E111,indentation is not a multiple of four,✔,pycodestyle_
    Indentation,E112,expected an indented block,✔,pycodestyle_
    Indentation,E113,unexpected indentation,✔,pycodestyle_
    Indentation,E114,indentation is not a multiple of four (comment),✔,pycodestyle_
    Indentation,E115,expected an indented block (comment),✔,pycodestyle_
    Indentation,E116,unexpected indentation (comment),✔,pycodestyle_
    Indentation,E117,over-indented,✔,pycodestyle_
    Indentation,E121,continuation line under-indented for hanging indent,×,pycodestyle_
    Indentation,E122,continuation line missing indentation or outdented,✔,pycodestyle_
    Indentation,E123,closing bracket does not match indentation of opening bracket`s line,×,pycodestyle_
    Indentation,E124,closing bracket does not match visual indentation,✔,pycodestyle_
    Indentation,E125,continuation line with same indent as next logical line,✔,pycodestyle_
    Indentation,E126,continuation line over-indented for hanging indent,×,pycodestyle_
    Indentation,E127,continuation line over-indented for visual indent,✔,pycodestyle_
    Indentation,E128,continuation line under-indented for visual indent,✔,pycodestyle_
    Indentation,E129,visually indented line with same indent as next logical line,✔,pycodestyle_
    Indentation,E131,continuation line unaligned for hanging indent,✔,pycodestyle_
    Indentation,E133,closing bracket is missing indentation,×,pycodestyle_
    Whitespace,E201,whitespace after `(`,✔,pycodestyle_
    Whitespace,E202,whitespace before `)`,✔,pycodestyle_
    Whitespace,E203,whitespace before `:`,✔,pycodestyle_
    Whitespace,E211,whitespace before `(`,✔,pycodestyle_
    Whitespace,E221,multiple spaces before operator,✔,pycodestyle_
    Whitespace,E222,multiple spaces after operator,✔,pycodestyle_
    Whitespace,E223,tab before operator,✔,pycodestyle_
    Whitespace,E224,tab after operator,✔,pycodestyle_
    Whitespace,E225,missing whitespace around operator,✔,pycodestyle_
    Whitespace,E226,missing whitespace around arithmetic operator,×,pycodestyle_
    Whitespace,E227,missing whitespace around bitwise or shift operator,✔,pycodestyle_
    Whitespace,E228,missing whitespace around modulo operator,✔,pycodestyle_
    Whitespace,E231,"missing whitespace after `,`, `;`, or `:`",✔,pycodestyle_
    Whitespace,E241,"multiple spaces after `,`",×,pycodestyle_
    Whitespace,E242,"tab after `,`",×,pycodestyle_
    Whitespace,E251,unexpected spaces around keyword / parameter equals,✔,pycodestyle_
    Whitespace,E261,at least two spaces before inline comment,✔,pycodestyle_
    Whitespace,E262,inline comment should start with `# `,✔,pycodestyle_
    Whitespace,E265,block comment should start with `# `,✔,pycodestyle_
    Whitespace,E266,too many leading `#` for block comment,✔,pycodestyle_
    Whitespace,E271,multiple spaces after keyword,✔,pycodestyle_
    Whitespace,E272,multiple spaces before keyword,✔,pycodestyle_
    Whitespace,E273,tab after keyword,✔,pycodestyle_
    Whitespace,E274,tab before keyword,✔,pycodestyle_
    Whitespace,E275,missing whitespace after keyword,✔,pycodestyle_
    Blank line,E301,"expected 1 blank line, found 0",✔,pycodestyle_
    Blank line,E302,"expected 2 blank lines, found 0",✔,pycodestyle_
    Blank line,E303,too many blank lines (3),✔,pycodestyle_
    Blank line,E304,blank lines found after function decorator,✔,pycodestyle_
    Blank line,E305,expected 2 blank lines after end of function or class,✔,pycodestyle_
    Blank line,E306,expected 1 blank line before a nested definition,✔,pycodestyle_
    Import,E401,multiple imports on one line,✔,pycodestyle_
    Import,E402,module level import not at top of file,✔,pycodestyle_
    Line length,E501,line too long (82 > 79 characters),✔,pycodestyle_
    Line length,E502,the backslash is redundant between brackets,✔,pycodestyle_
    Statement,E701,multiple statements on one line (colon),✔,pycodestyle_
    Statement,E702,multiple statements on one line (semicolon),✔,pycodestyle_
    Statement,E703,statement ends with a semicolon,✔,pycodestyle_
    Statement,E704,multiple statements on one line (def),×,pycodestyle_
    Statement,E711,comparison to None should be `if cond is None:`,✔,pycodestyle_
    Statement,E712,comparison to True should be `if cond is True:` or `if cond:`,✔,pycodestyle_
    Statement,E713,test for membership should be `not in`,✔,pycodestyle_
    Statement,E714,test for object identity should be `is not`,✔,pycodestyle_
    Statement,E721,"do not compare types, use `isinstance()`",✔,pycodestyle_
    Statement,E722,"do not use bare except, specify exception instead",✔,pycodestyle_
    Statement,E731,"do not assign a lambda expression, use a def",✔,pycodestyle_
    Statement,E741,"do not use variables named `l`, `O`, or `I`",✔,pycodestyle_
    Statement,E742,"do not define classes named `l`, `O`, or `I`",✔,pycodestyle_
    Statement,E743,"do not define functions named `l`, `O`, or `I`",✔,pycodestyle_
    Runtime,E901,SyntaxError or IndentationError,✔,pycodestyle_
    Runtime,E902,IOError,✔,pycodestyle_
    E9,E999,fail to compile a file into an Abstract Syntax Tree for the plugins that require it,✔,pyflakes_
    F4,F401,module imported but unused,✔,pyflakes_
    F4,F402,import module from line N shadowed by loop variable,✔,pyflakes_
    F4,F403,`from module import *` used; unable to detect undefined names,✔,pyflakes_
    F4,F404,future import(s) name after other statements,✔,pyflakes_
    F4,F405,"name may be undefined, or defined from star imports: module",✔,pyflakes_
    F4,F406,`from module import *` only allowed at module level,✔,pyflakes_
    F4,F407,an undefined __future__ feature name was imported,✔,pyflakes_
    F6,F601,dictionary key name repeated with different values,✔,pyflakes_
    F6,F602,dictionary key variable name repeated with different values,✔,pyflakes_
    F6,F621,too many expressions in an assignment with star-unpacking,✔,pyflakes_
    F6,F622,"two or more starred expressions in an assignment (a, *b, *c = d)",✔,pyflakes_
    F6,F631,"assertion test is a tuple, which are always True",✔,pyflakes_
    F6,F632,"use ==/!= to compare str , bytes , and int literals",✔,pyflakes_
    F6,F633,use of >> is invalid with print function,✔,pyflakes_
    F7,F701,a break statement outside of a while or for loop,✔,pyflakes_
    F7,F702,a continue statement outside of a while or for loop,✔,pyflakes_
    F7,F703,a continue statement in a finally block in a loop,✔,pyflakes_
    F7,F704,a yield or yield from statement outside of a function,✔,pyflakes_
    F7,F705,a return statement with arguments inside a generator,✔,pyflakes_
    F7,F706,a return statement outside of a function/method,✔,pyflakes_
    F7,F707,an except: block as not the last exception handler,✔,pyflakes_
    F7,F721,syntax error in doctest,✔,pyflakes_
    F7,F722,syntax error in forward annotation,✔,pyflakes_
    F7,F723,syntax error in type comment,✔,pyflakes_
    F8,F811,redefinition of unused name from line N,✔,pyflakes_
    F8,F812,list comprehension redefines name from line N,✔,pyflakes_
    F8,F821,undefined name name,✔,pyflakes_
    F8,F822,undefined name name in __all__,✔,pyflakes_
    F8,F823,local variable name … referenced before assignment,✔,pyflakes_
    F8,F831,duplicate argument name in function definition,✔,pyflakes_
    F8,F841,local variable name is assigned to but never used,✔,pyflakes_
    F9,F901,raise NotImplemented should be raise NotImplementedError,✔,pyflakes_
    Indentation warning,W191,indentation contains tabs,✔,pycodestyle_
    Whitespace warning,W291,trailing whitespace,✔,pycodestyle_
    Whitespace warning,W292,no newline at end of file,✔,pycodestyle_
    Whitespace warning,W293,blank line contains whitespace,✔,pycodestyle_
    Blank line warning,W391,blank line at end of file,✔,pycodestyle_
    Line break warning,W503,line break before binary operator,×,pycodestyle_
    Line break warning,W504,line break after binary operator,×,pycodestyle_
    Line break warning,W505,doc line too long (82 > 79 characters),×,pycodestyle_
    Deprecation warning,W601,".has_key() is deprecated, use `in`",✔,pycodestyle_
    Deprecation warning,W602,deprecated form of raising exception,✔,pycodestyle_
    Deprecation warning,W603,"`<>` is deprecated, use `!=`",✔,pycodestyle_
    Deprecation warning,W604,"backticks are deprecated, use `repr()`",✔,pycodestyle_
    Deprecation warning,W605,invalid escape sequence `x`,✔,pycodestyle_
    Deprecation warning,W606,`async` and `await` are reserved keywords starting with Python 3.7,✔,pycodestyle_

Sources
-------

* pydocstyle_ - a tool to check your Python code against some of the style conventions in PEP 8
* pyflakes_- A simple program which checks Python source files for errors.
* pycodestyle_ - a tool to check your Python code against some of the style conventions in PEP 8

TODO: Extract codes from external plugins:
https://github.com/DmytroLitvinov/awesome-flake8-extensions

.. _pydocstyle: http://www.pydocstyle.org/en/latest/error_codes.html
.. _pyflakes: http://flake8.pycqa.org/en/latest/user/error-codes.html
.. _pycodestyle: http://pycodestyle.pycqa.org/en/latest/intro.html#error-codes

