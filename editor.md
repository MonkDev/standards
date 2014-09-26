Editor
======

1.  Any editor may be used. That said, [Sublime Text](http://www.sublimetext.com)
    is recommended and used by most of the team.
2.  Each project should setup an [EditorConfig](http://editorconfig.org) that's
    applied by [a supported editor plugin](http://editorconfig.org/#download).
    See below for a recommended baseline config.

EditorConfig
------------

1.  The following config should serve as a baseline and be modified for the
    project-specific language/framework:

    ```ini
    # EditorConfig: http://editorconfig.org

    root = true

    [*]
    indent_style = space
    indent_size = 2
    end_of_line = lf
    charset = utf-8
    trim_trailing_whitespace = true
    insert_final_newline = true

    [*.md]
    trim_trailing_whitespace = false
    ```
