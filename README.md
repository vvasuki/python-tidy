python-tidy
===========

Cleans up, regularizes, and reformats the text of Python scripts. Suitable for use with eclipse.  This tool does some common fixes without the coder having to go do it himself. It need not be complete - one can always fix things it cannot handle manually. Forked from http://pypi.python.org/pypi/PythonTidy .

For use with eclipse:
  a] Ensure PythonTidy.py can be invoked from the shell
     without supplying the directory.
  b] Copy pyedit_pythontidy.py somewhere and supply its path to Eclipse in:
     Windows - Preferences - Pydev - Scripting Pydev.
  c] ALERT: Errors in PythonTidy.py will result in an empty string
      replacing the code in the edit window. Use UNDO in that case.
