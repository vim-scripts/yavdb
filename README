This is a mirror of http://www.vim.org/scripts/script.php?script_id=1954

This is a generic Vim <->Debugger Interface Tool designed to be adaptable to any debugger application.  Currently supported debuggers include jdb and gdb.

Script Requirements:
-VIM compiled with Signs, Client-Server, and Python support.
-Python 2.5
-An operating system with support for named pipes

Using YAVDB:

  yavdb [-s servername] [-t type] <debugger command line>

-s specifies the Vim servername.  If no VIM (or GVIM) window exists with this servername, a new GVIM window will be opened.  If not specified, the servername 'VimDebugger' will be used.  If multiple applications are being debugged simultaneously unique servernames must be used.

-t can be used to override the debugger type.  If this option is omitted the debugger name will be used as the type.  Currently supported debugger types include 'gdb' and 'jdb'.  Note that jdb will only correctly notify VIM of events when classnames are identical to filenames (other than the .java extension).

VIM will have the following key mappings set:

<C-F5> Run Application
<F5> Continue Execution
<F7> Step Into a Function
<F8> Next Instruction
<F9> Set Breakpoint
<F10> Print variable value under cursor

