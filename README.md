When you install diffvg on windows you meet:: File "setup.py", line 39, in build_extension '-DPYTHON_LIBRARY=' + get_config_var('LIBDIR'), TypeError: can only concatenate str (not "NoneType") to str.

Replace setup.py with this file
