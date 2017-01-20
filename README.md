information about the contents of this repository.

<pre>
Michaels-MacBook-Pro-3:Environment_alias zen1$ git clone --recursive https://github.com/MichaelDimmitt/Code-for-the-book-Artificial-Intelligence-Modern-Approach-.git
Cloning into 'Code-for-the-book-Artificial-Intelligence-Modern-Approach-'...
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 1), reused 5 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
Checking connectivity... done.
Submodule 'aima-csharp' (https://github.com/aimacode/aima-csharp.git) registered for path 'aima-csharp'
Submodule 'aima-java' (https://github.com/aimacode/aima-java.git) registered for path 'aima-java'
Submodule 'aima-javascript' (https://github.com/aimacode/aima-javascript.git) registered for path 'aima-javascript'
Submodule 'aima-lisp' (https://github.com/aimacode/aima-lisp.git) registered for path 'aima-lisp'
Submodule 'aima-python' (https://github.com/aimacode/aima-python) registered for path 'aima-python'
Submodule 'aima-scala' (https://github.com/aimacode/aima-scala.git) registered for path 'aima-scala'
Cloning into 'aima-csharp'...
remote: Counting objects: 718, done.
remote: Total 718 (delta 0), reused 0 (delta 0), pack-reused 718
Receiving objects: 100% (718/718), 209.85 KiB | 0 bytes/s, done.
Resolving deltas: 100% (374/374), done.
Checking connectivity... done.
Submodule path 'aima-csharp': checked out '204b7e5185345c74f15a55584baf9a7511d57cfd'
Cloning into 'aima-java'...
remote: Counting objects: 30285, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 30285 (delta 0), reused 0 (delta 0), pack-reused 30281
Receiving objects: 100% (30285/30285), 139.46 MiB | 9.74 MiB/s, done.
Resolving deltas: 100% (18536/18536), done.
Checking connectivity... done.
Submodule path 'aima-java': checked out 'b1df7055359c7047e07199355fea1fa40bb84bcd'
Cloning into 'aima-javascript'...
remote: Counting objects: 506, done.
remote: Total 506 (delta 0), reused 0 (delta 0), pack-reused 506
Receiving objects: 100% (506/506), 561.94 KiB | 0 bytes/s, done.
Resolving deltas: 100% (227/227), done.
Checking connectivity... done.
Submodule path 'aima-javascript': checked out 'dbce029383415fdedff3a1fddd8e59c7f466a8d8'
fatal: no submodule mapping found in .gitmodules for path '.publish'
Failed to recurse into submodule path 'aima-javascript'
Michaels-MacBook-Pro-3:Environment_alias zen1$ cd Code-for-the-book-Artificial-Intelligence-Modern-Approach-/
Michaels-MacBook-Pro-3:Code-for-the-book-Artificial-Intelligence-Modern-Approach- zen1$ for d in ./*/ ; do (cd "$d" && echo "$d" && cloc --vcs git); done
./aima-csharp/
     211 text files.
     211 unique files.                                          
       4 files ignored.

github.com/AlDanial/cloc v 1.68  T=0.25 s (842.0 files/s, 89723.1 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
C#                             205           2445           5403          13931
MSBuild script                   1              0              7            269
Markdown                         1              0              0              2
-------------------------------------------------------------------------------
SUM:                           207           2445           5410          14202
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
./aima-java/
     994 text files.
     990 unique files.                                          
     101 files ignored.

github.com/AlDanial/cloc v 1.68  T=1.06 s (851.1 files/s, 90676.5 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Java                           889          12170          22854          60278
Ant                              4             40              2            245
Markdown                         3             17              0            201
Maven                            1              6              6             84
HTML                             3              9              0             76
YAML                             1              2              0              5
-------------------------------------------------------------------------------
SUM:                           901          12244          22862          60889
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
./aima-javascript/
     115 text files.
     114 unique files.                                          
Complex regular subexpression recursion limit (32766) exceeded at /usr/local/bin/cloc line 7272.
       9 files ignored.

github.com/AlDanial/cloc v 1.68  T=0.20 s (566.4 files/s, 90521.7 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
JavaScript                      72           3008           2821           9982
HTML                            30            232              1           1103
CSS                              4              7             32            349
Markdown                         2             32              0            108
JSON                             2              0              0             62
YAML                             1              0              0              3
-------------------------------------------------------------------------------
SUM:                           111           3279           2854          11607
-------------------------------------------------------------------------------
Saving session...
...saving history...truncating history files...
...completed.
./aima-lisp/
       0 text files.
       0 unique files.                              
       0 files ignored.
Saving session...
...saving history...truncating history files...
...completed.
./aima-python/
       0 text files.
       0 unique files.                              
       0 files ignored.
Saving session...
...saving history...truncating history files...
...completed.
./aima-scala/
       0 text files.
       0 unique files.                              
       0 files ignored.
Saving session...
...saving history...truncating history files...
...completed.

</pre>
