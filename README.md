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
</pre>
<br><br>

<pre>
for d in ./*/ ; do (cd "$d" && echo "$d" && cloc --vcs git); done
./aima-csharp/
     211 text files.
     211 unique files.                                          
       4 files ignored.

github.com/AlDanial/cloc v 1.72  T=0.33 s (623.0 files/s, 66385.6 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
C#                             205           2445           5403          13931
MSBuild script                   1              0              7            269
Markdown                         1              0              0              2
-------------------------------------------------------------------------------
SUM:                           207           2445           5410          14202
-------------------------------------------------------------------------------
./aima-java/
     994 text files.
     990 unique files.                                          
     101 files ignored.

github.com/AlDanial/cloc v 1.72  T=1.55 s (581.9 files/s, 61995.9 lines/s)
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
./aima-javascript/
     115 text files.
     114 unique files.                                          
Complex regular subexpression recursion limit (32766) exceeded at /usr/local/Cellar/cloc/1.72/libexec/bin/cloc line 7573.
       9 files ignored.

github.com/AlDanial/cloc v 1.72  T=0.27 s (409.2 files/s, 65394.9 lines/s)
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
./aima-lisp/
     116 text files.
     113 unique files.                                          
       6 files ignored.

github.com/AlDanial/cloc v 1.72  T=0.25 s (445.3 files/s, 56648.1 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Lisp                            88           1248            896           6573
HTML                            21            219             20           5031
Markdown                         1              2              0              5
-------------------------------------------------------------------------------
SUM:                           110           1469            916          11609
-------------------------------------------------------------------------------
./aima-python/
      61 text files.
      61 unique files.                              
      38 files ignored.

github.com/AlDanial/cloc v 1.72  T=0.21 s (163.4 files/s, 46872.5 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Python                          28           1916           1845           5643
JavaScript                       3             29             42            261
Markdown                         2             56              0            194
make                             1             13              1             20
YAML                             1              6              0             17
-------------------------------------------------------------------------------
SUM:                            35           2020           1888           6135
-------------------------------------------------------------------------------
./aima-scala/
      48 text files.
      48 unique files.                              
       6 files ignored.

github.com/AlDanial/cloc v 1.72  T=0.12 s (351.9 files/s, 13614.6 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Scala                           40            305            111           1184
Markdown                         1              3              0             12
YAML                             1              0              0             10
-------------------------------------------------------------------------------
SUM:                            42            308            111           1206
-------------------------------------------------------------------------------
</pre>



http://www3.cs.stonybrook.edu/~algorith/book/programs/
http://www.algorist.com/algowiki/index.php/The_Algorithms_Design_Manual_(Second_Edition)

https://news.ycombinator.com/item?id=2914112

https://github.com/gzc/CLRS

knuth down;oadable programs
http://www-cs-faculty.stanford.edu/~uno/programs.html
