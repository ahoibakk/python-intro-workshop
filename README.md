# Python intro Workshop

A very quick introduction to the Python programming language trough doing exercises.

## Prerequisites

 - VS Code
 - Docker

## Setting up the environment

Instead of using the time on the workshop to install python on the computer. We will use 
the VSCode Remote Development extension.

You can find the extension by searching after `Remote Development` in the extension tab. 
Or by using the extension id `ms-vscode-remote.vscode-remote-extensionpack` directly.


[Python for developers - Cheat sheet](Python-for-developers-cheat-sheet.md)




## Topics
 - Language basics
    - Print (Hello world)
    - Intendention - 4 spaces. No curly brackets here. :(
    - Conditionals
        - if/elif/else
    - Loop / Iteration
        - for
            - for number in <list, set> 
                - range() is your friend
            - for index, value in enumerate(<list, set>)
                - instead of going for range(len(<list,set>))
        - while
        - break / continue
    - Comparison mosty as normal
        - Chained comparison
            - if 3 < x < 5
            - same as: if x > 3 and x < 5
        - Boolean operators
            - and, or, not instead of &&, ||, != (but != is valid. But using "not" is more pythonic)
    - Other
        - Try / catch
        - With
        - Slicing of lists
            - Negative indexing
                - a[-X] can be viewed as a[len(a)-X]
        - Pass - the "null/noop operation".
    - Types in stdlib
        - Dictionary, List, Set (Mutable)
        - Integer, String, Tuple (Immuatable)
        - String formatting.
            - Old and new ways. Use new way! (Needs Python 3.6 and above)
    - Math
        - Most notably difference: ** is power of. Not ^ as others
        - Integer division quirk. 3/4 => 0, 3/4. => 0.75. (Use // - Only Python 3)
    - Comments, only # .. No multiline
    - None == NULL
    - Functions
        - Def keyword
        - Default parameters
    - Objects and classes
        - object
        - dunder init (ctor) `__init__`
        - self is first paramter of all class methods
        - inheritance => subclassing
    - File IO
        - open/close
        - use the with keyword for implicit closing of io :)
    - PEP 8 (Have a read, but we will not go into details here now)
 - Modules
 - Pip / Packages