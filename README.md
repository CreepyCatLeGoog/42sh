# 42sh

tcsh-like shell
Command-line interpreter

Features

    Prompt with line edition
    Builtins alias, bg, cd, echo, exit, export, fg, hash, jobs, set, source, test, type, unalias, unset
    Executing simple commands
    Execute in background &
    Redirection >, >>, < and |
    Heredoc <<
    Logical operands && and ||
    Separator ;
    Inhibitors ", ' and \
    Environment and local variables $VAR or ${VAR}

Rules make

    make compiles the binary executable
    make clean delete all .o files
    make fclean delete all .o files and ./42sh
    make re does fclean and make
