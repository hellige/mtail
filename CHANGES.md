mtail 1.3.0:
  * mtail has been converted to python 3. thanks to lucas c villa real
    (@lucasvr) for this work!

mtail 1.2.0:
  * added --tty option. if --tty is specified and stdout is not a tty,
    no coloring is performed, although filters still apply. this is similar in
    spirit to the --color=auto option of gnu ls (thanks to hisham muhammad for
    this idea).
  * various small changes to support jython.
  * added allow/deny filters.

mtail 1.1.1:
  * changed threading/signal handling code to accommodate changes in
    python 2.0 (thanks to joseph grossberg for the bug report).

mtail 1.1.0:
  * added support for tailing multiple files.
  * added -v and -q options (and long versions) related to filename banner
    printing.
  * very minor bugfixes.
  * added --config option to explicitly specify config file.

mtail 1.0.0:
  * nothing but minor README updates.

mtail 0.9.2:
  * fixed bug that occurred if there was no config file.
  * changed indenting style (all tabs are now spaces). i don't know why they
    were all tabs in the first place... i've never liked it that way. :)
  * slight change to warranty disclaimer.
  * fixed bug that occurred if the environment variable HOME was unset.

mtail 0.9.1:
  * fixed bug regarding tailing of stdin.
  * added semi-formal license.

mtail 0.9.0:
  * initial released version.
