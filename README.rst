.. csv-table:: Flake8 Errors
    :header: "Section" "Code" "Example Message" "Default" "Source"
    :widths: 10, 5, 20, 5, 10

    C9,C901,'function' is too complex (##),TRUE,[pyflakes]_
    Missing Docstrings,D100,Missing docstring in public module,TRUE,[pydocstyle]_
    Missing Docstrings,D101,Missing docstring in public class,TRUE,[pydocstyle]_
    Missing Docstrings,D102,Missing docstring in public method,TRUE,[pydocstyle]_
    Missing Docstrings,D103,Missing docstring in public function,TRUE,[pydocstyle]_
    Missing Docstrings,D104,Missing docstring in public package,TRUE,[pydocstyle]_
    Missing Docstrings,D105,Missing docstring in magic method,TRUE,[pydocstyle]_
    Missing Docstrings,D106,Missing docstring in public nested class,TRUE,[pydocstyle]_
    Missing Docstrings,D107,Missing docstring in __init__,TRUE,[pydocstyle]_
    Whitespace Issues,D200,One-line docstring should fit on one line with quotes,TRUE,[pydocstyle]_
    Whitespace Issues,D201,No blank lines allowed before function docstring,TRUE,[pydocstyle]_
    Whitespace Issues,D202,No blank lines allowed after function docstring,TRUE,[pydocstyle]_
    Whitespace Issues,D203,1 blank line required before class docstring,TRUE,[pydocstyle]_
    Whitespace Issues,D204,1 blank line required after class docstring,TRUE,[pydocstyle]_
    Whitespace Issues,D205,1 blank line required between summary line and description,TRUE,[pydocstyle]_
    Whitespace Issues,D206,"Docstring should be indented with spaces, not tabs",TRUE,[pydocstyle]_
    Whitespace Issues,D207,Docstring is under-indented,TRUE,[pydocstyle]_
    Whitespace Issues,D208,Docstring is over-indented,TRUE,[pydocstyle]_
    Whitespace Issues,D209,Multi-line docstring closing quotes should be on a separate line,TRUE,[pydocstyle]_
    Whitespace Issues,D210,No whitespaces allowed surrounding docstring text,TRUE,[pydocstyle]_
    Whitespace Issues,D211,No blank lines allowed before class docstring,TRUE,[pydocstyle]_
    Whitespace Issues,D212,Multi-line docstring summary should start at the first line,TRUE,[pydocstyle]_
    Whitespace Issues,D213,Multi-line docstring summary should start at the second line,TRUE,[pydocstyle]_
    Whitespace Issues,D214,Section is over-indented,TRUE,[pydocstyle]_
    Whitespace Issues,D215,Section underline is over-indented,TRUE,[pydocstyle]_
    Quotes Issues,D300,Use “”“triple double quotes”“”,TRUE,[pydocstyle]_
    Quotes Issues,D301,Use r”“” if any backslashes in a docstring,TRUE,[pydocstyle]_
    Quotes Issues,D302,Use u”“” for Unicode docstrings,TRUE,[pydocstyle]_
    Docstring Content Issues,D400,First line should end with a period,TRUE,[pydocstyle]_
    Docstring Content Issues,D401,First line should be in imperative mood,TRUE,[pydocstyle]_
    Docstring Content Issues,D401,First line should be in imperative mood; try rephrasing,TRUE,[pydocstyle]_
    Docstring Content Issues,D402,First line should not be the function’s “signature”,TRUE,[pydocstyle]_
    Docstring Content Issues,D403,First word of the first line should be properly capitalized,TRUE,[pydocstyle]_
    Docstring Content Issues,D404,First word of the docstring should not be This,TRUE,[pydocstyle]_
    Docstring Content Issues,D405,Section name should be properly capitalized,TRUE,[pydocstyle]_
    Docstring Content Issues,D406,Section name should end with a newline,TRUE,[pydocstyle]_
    Docstring Content Issues,D407,Missing dashed underline after section,TRUE,[pydocstyle]_
    Docstring Content Issues,D408,Section underline should be in the line following the section’s name,TRUE,[pydocstyle]_
    Docstring Content Issues,D409,Section underline should match the length of its name,TRUE,[pydocstyle]_
    Docstring Content Issues,D410,Missing blank line after section,TRUE,[pydocstyle]_
    Docstring Content Issues,D411,Missing blank line before section,TRUE,[pydocstyle]_
    Docstring Content Issues,D412,No blank lines allowed between a section header and its content,TRUE,[pydocstyle]_
    Docstring Content Issues,D413,Missing blank line after last section,TRUE,[pydocstyle]_
    Docstring Content Issues,D414,Section has no content,TRUE,[pydocstyle]_
    Docstring Content Issues,D415,"First line should end with a period, question mark, or exclamation point",TRUE,[pydocstyle]_
    Docstring Content Issues,D416,Section name should end with a colon,TRUE,[pydocstyle]_
    Docstring Content Issues,D417,Missing argument descriptions in the docstring,TRUE,[pydocstyle]_
    Indentation,E101,indentation contains mixed spaces and tabs,TRUE,[pycodestyle]_
    Indentation,E111,indentation is not a multiple of four,TRUE,[pycodestyle]_
    Indentation,E112,expected an indented block,TRUE,[pycodestyle]_
    Indentation,E113,unexpected indentation,TRUE,[pycodestyle]_
    Indentation,E114,indentation is not a multiple of four (comment),TRUE,[pycodestyle]_
    Indentation,E115,expected an indented block (comment),TRUE,[pycodestyle]_
    Indentation,E116,unexpected indentation (comment),TRUE,[pycodestyle]_
    Indentation,E117,over-indented,TRUE,[pycodestyle]_
    Indentation,E121,continuation line under-indented for hanging indent,FALSE,[pycodestyle]_
    Indentation,E122,continuation line missing indentation or outdented,TRUE,[pycodestyle]_
    Indentation,E123,closing bracket does not match indentation of opening bracket’s line,FALSE,[pycodestyle]_
    Indentation,E124,closing bracket does not match visual indentation,TRUE,[pycodestyle]_
    Indentation,E125,continuation line with same indent as next logical line,TRUE,[pycodestyle]_
    Indentation,E126,continuation line over-indented for hanging indent,FALSE,[pycodestyle]_
    Indentation,E127,continuation line over-indented for visual indent,TRUE,[pycodestyle]_
    Indentation,E128,continuation line under-indented for visual indent,TRUE,[pycodestyle]_
    Indentation,E129,visually indented line with same indent as next logical line,TRUE,[pycodestyle]_
    Indentation,E131,continuation line unaligned for hanging indent,TRUE,[pycodestyle]_
    Indentation,E133,closing bracket is missing indentation,FALSE,[pycodestyle]_
    Whitespace,E201,whitespace after ‘(‘,TRUE,[pycodestyle]_
    Whitespace,E202,whitespace before ‘)’,TRUE,[pycodestyle]_
    Whitespace,E203,whitespace before ‘:’,TRUE,[pycodestyle]_
    Whitespace,E211,whitespace before ‘(‘,TRUE,[pycodestyle]_
    Whitespace,E221,multiple spaces before operator,TRUE,[pycodestyle]_
    Whitespace,E222,multiple spaces after operator,TRUE,[pycodestyle]_
    Whitespace,E223,tab before operator,TRUE,[pycodestyle]_
    Whitespace,E224,tab after operator,TRUE,[pycodestyle]_
    Whitespace,E225,missing whitespace around operator,TRUE,[pycodestyle]_
    Whitespace,E226,missing whitespace around arithmetic operator,FALSE,[pycodestyle]_
    Whitespace,E227,missing whitespace around bitwise or shift operator,TRUE,[pycodestyle]_
    Whitespace,E228,missing whitespace around modulo operator,TRUE,[pycodestyle]_
    Whitespace,E231,"missing whitespace after ‘,’, ‘;’, or ‘:’",TRUE,[pycodestyle]_
    Whitespace,E241,"multiple spaces after ‘,’",FALSE,[pycodestyle]_
    Whitespace,E242,"tab after ‘,’",FALSE,[pycodestyle]_
    Whitespace,E251,unexpected spaces around keyword / parameter equals,TRUE,[pycodestyle]_
    Whitespace,E261,at least two spaces before inline comment,TRUE,[pycodestyle]_
    Whitespace,E262,inline comment should start with ‘# ‘,TRUE,[pycodestyle]_
    Whitespace,E265,block comment should start with ‘# ‘,TRUE,[pycodestyle]_
    Whitespace,E266,too many leading ‘#’ for block comment,TRUE,[pycodestyle]_
    Whitespace,E271,multiple spaces after keyword,TRUE,[pycodestyle]_
    Whitespace,E272,multiple spaces before keyword,TRUE,[pycodestyle]_
    Whitespace,E273,tab after keyword,TRUE,[pycodestyle]_
    Whitespace,E274,tab before keyword,TRUE,[pycodestyle]_
    Whitespace,E275,missing whitespace after keyword,TRUE,[pycodestyle]_
    Blank line,E301,"expected 1 blank line, found 0",TRUE,[pycodestyle]_
    Blank line,E302,"expected 2 blank lines, found 0",TRUE,[pycodestyle]_
    Blank line,E303,too many blank lines (3),TRUE,[pycodestyle]_
    Blank line,E304,blank lines found after function decorator,TRUE,[pycodestyle]_
    Blank line,E305,expected 2 blank lines after end of function or class,TRUE,[pycodestyle]_
    Blank line,E306,expected 1 blank line before a nested definition,TRUE,[pycodestyle]_
    Import,E401,multiple imports on one line,TRUE,[pycodestyle]_
    Import,E402,module level import not at top of file,TRUE,[pycodestyle]_
    Line length,E501,line too long (82 > 79 characters),TRUE,[pycodestyle]_
    Line length,E502,the backslash is redundant between brackets,TRUE,[pycodestyle]_
    Statement,E701,multiple statements on one line (colon),TRUE,[pycodestyle]_
    Statement,E702,multiple statements on one line (semicolon),TRUE,[pycodestyle]_
    Statement,E703,statement ends with a semicolon,TRUE,[pycodestyle]_
    Statement,E704,multiple statements on one line (def),FALSE,[pycodestyle]_
    Statement,E711,comparison to None should be ‘if cond is None:’,TRUE,[pycodestyle]_
    Statement,E712,comparison to True should be ‘if cond is True:’ or ‘if cond:’,TRUE,[pycodestyle]_
    Statement,E713,test for membership should be ‘not in’,TRUE,[pycodestyle]_
    Statement,E714,test for object identity should be ‘is not’,TRUE,[pycodestyle]_
    Statement,E721,"do not compare types, use ‘isinstance()’",TRUE,[pycodestyle]_
    Statement,E722,"do not use bare except, specify exception instead",TRUE,[pycodestyle]_
    Statement,E731,"do not assign a lambda expression, use a def",TRUE,[pycodestyle]_
    Statement,E741,"do not use variables named ‘l’, ‘O’, or ‘I’",TRUE,[pycodestyle]_
    Statement,E742,"do not define classes named ‘l’, ‘O’, or ‘I’",TRUE,[pycodestyle]_
    Statement,E743,"do not define functions named ‘l’, ‘O’, or ‘I’",TRUE,[pycodestyle]_
    Runtime,E901,SyntaxError or IndentationError,TRUE,[pycodestyle]_
    Runtime,E902,IOError,TRUE,[pycodestyle]_
    E9,E999,fail to compile a file into an Abstract Syntax Tree for the plugins that require it,TRUE,[pyflakes]_
    F4,F401,module imported but unused,TRUE,[pyflakes]_
    F4,F402,import module from line N shadowed by loop variable,TRUE,[pyflakes]_
    F4,F403,‘from module import *’ used; unable to detect undefined names,TRUE,[pyflakes]_
    F4,F404,future import(s) name after other statements,TRUE,[pyflakes]_
    F4,F405,"name may be undefined, or defined from star imports: module",TRUE,[pyflakes]_
    F4,F406,‘from module import *’ only allowed at module level,TRUE,[pyflakes]_
    F4,F407,an undefined __future__ feature name was imported,TRUE,[pyflakes]_
    F6,F601,dictionary key name repeated with different values,TRUE,[pyflakes]_
    F6,F602,dictionary key variable name repeated with different values,TRUE,[pyflakes]_
    F6,F621,too many expressions in an assignment with star-unpacking,TRUE,[pyflakes]_
    F6,F622,"two or more starred expressions in an assignment (a, *b, *c = d)",TRUE,[pyflakes]_
    F6,F631,"assertion test is a tuple, which are always True",TRUE,[pyflakes]_
    F6,F632,"use ==/!= to compare str , bytes , and int literals",TRUE,[pyflakes]_
    F6,F633,use of >> is invalid with print function,TRUE,[pyflakes]_
    F7,F701,a break statement outside of a while or for loop,TRUE,[pyflakes]_
    F7,F702,a continue statement outside of a while or for loop,TRUE,[pyflakes]_
    F7,F703,a continue statement in a finally block in a loop,TRUE,[pyflakes]_
    F7,F704,a yield or yield from statement outside of a function,TRUE,[pyflakes]_
    F7,F705,a return statement with arguments inside a generator,TRUE,[pyflakes]_
    F7,F706,a return statement outside of a function/method,TRUE,[pyflakes]_
    F7,F707,an except: block as not the last exception handler,TRUE,[pyflakes]_
    F7,F721,syntax error in doctest,TRUE,[pyflakes]_
    F7,F722,syntax error in forward annotation,TRUE,[pyflakes]_
    F7,F723,syntax error in type comment,TRUE,[pyflakes]_
    F8,F811,redefinition of unused name from line N,TRUE,[pyflakes]_
    F8,F812,list comprehension redefines name from line N,TRUE,[pyflakes]_
    F8,F821,undefined name name,TRUE,[pyflakes]_
    F8,F822,undefined name name in __all__,TRUE,[pyflakes]_
    F8,F823,local variable name … referenced before assignment,TRUE,[pyflakes]_
    F8,F831,duplicate argument name in function definition,TRUE,[pyflakes]_
    F8,F841,local variable name is assigned to but never used,TRUE,[pyflakes]_
    F9,F901,raise NotImplemented should be raise NotImplementedError,TRUE,[pyflakes]_
    Indentation warning,W191,indentation contains tabs,TRUE,[pycodestyle]_
    Whitespace warning,W291,trailing whitespace,TRUE,[pycodestyle]_
    Whitespace warning,W292,no newline at end of file,TRUE,[pycodestyle]_
    Whitespace warning,W293,blank line contains whitespace,TRUE,[pycodestyle]_
    Blank line warning,W391,blank line at end of file,TRUE,[pycodestyle]_
    Line break warning,W503,line break before binary operator,FALSE,[pycodestyle]_
    Line break warning,W504,line break after binary operator,FALSE,[pycodestyle]_
    Line break warning,W505,doc line too long (82 > 79 characters),FALSE,[pycodestyle]_
    Deprecation warning,W601,".has_key() is deprecated, use ‘in’",TRUE,[pycodestyle]_
    Deprecation warning,W602,deprecated form of raising exception,TRUE,[pycodestyle]_
    Deprecation warning,W603,"‘<>’ is deprecated, use ‘!=’",TRUE,[pycodestyle]_
    Deprecation warning,W604,"backticks are deprecated, use ‘repr()’",TRUE,[pycodestyle]_
    Deprecation warning,W605,invalid escape sequence ‘x’,TRUE,[pycodestyle]_
    Deprecation warning,W606,‘async’ and ‘await’ are reserved keywords starting with Python 3.7,TRUE,[pycodestyle]_


.. [pydocstyle] http://www.pydocstyle.org/en/latest/error_codes.html
.. [pyflakes] http://flake8.pycqa.org/en/latest/user/error-codes.html
.. [pycodestyle] http://pycodestyle.pycqa.org/en/latest/intro.html#error-codes

