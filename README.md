# sea_shell
## A unix shell in C

This custom shell takes 4 internal commands:

    cd
    history
    pwd
    exit

    This shell also takes all the external commands listed in /bin
    It can take multiple arguments like : ls -l -a -ih or: cat -n f1 f2 f3 f4
    It can also handle cases like :$ ls -a -l which have multiple spaces.
    Typing only cd will also work
    We can also run shell inside a shell, bash & other are also supported & can also compile this shell inside & run again.
    Colour scheme makes it attractive :P
    Limitations : Empty input doesn't work (but with space & tab it works) No. of quotes dont matter in echo, it removes all

# To do :
Add feature for `echo` command
