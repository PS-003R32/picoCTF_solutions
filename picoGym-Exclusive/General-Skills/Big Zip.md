Description
Unzip this archive and find the flag.
    [Download zip file](https://artifacts.picoctf.net/c/504/big-zip-files.zip)

In this easy level challenge we will use the grp command to find the flag.
the unziped folder has many files and directories inside which will make it very hard to find the flag.
we will use the grep command to recursively find the expression.
Command: '$grep -r picoCTF'

this will return the flag: picoCTF{gr3p_15_m4g1c_ef8790dc}
