random-file
===========

A Python 3 script to return the name of a randomly selected file in a
directory.

    Usage:
      rndfile [options] [DIRECTORY]
      rndfile -h | --help
      rndfile -v | --version
     
    Arguments:
      DIRECTORY           Directory from which to select [default: .].
     
    Options:
      -h, --help          Show this screen.
      -v, --version       Show version.
      -f, --full          Return full pathname of selected file.
      -a, --all           Allow selection of dot (hidden) files.
      -p P, --pattern P   Comma separated list of filename pattern(s) 
                          (e.g., -p '*.gif, *.jpg, *.jpeg, *.png')
                          to restrict the selection (joined with nonexclusive OR).

