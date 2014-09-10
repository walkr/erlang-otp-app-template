Erlang App Template
-------------------
A general purpose template for writing Erlang apps.

### Structure ###

+ src

  Contains the Erlang source code.

+ ebin

  Contains the Erlang object code, the beam files. The .app file is also placed here.

+ priv

  Used for application specific files. For example, C executables are placed here. The function code:priv_dir/1 should be used to access this directory.

+ include

  Used for include files.
