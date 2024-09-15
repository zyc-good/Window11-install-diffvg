1. Download the packages at https://github.com/BachiLi/diffvg, and manually download the sub-installers pybind11 and trust and place them in the corresponding locations.
2. When you install diffvg on windows you meet:: File "setup.py", line 39, in build_extension '-DPYTHON_LIBRARY=' + get_config_var('LIBDIR'), TypeError: can only concatenate str (not "NoneType") to str.
3. Replace setup.py with this file.
