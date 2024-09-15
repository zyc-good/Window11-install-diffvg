1. Download the packages at https://github.com/BachiLi/diffvg, and manually download the sub-installers pybind11 and trust and place them in the corresponding locations.
2. When you install diffvg on windows you meet:: File "setup.py", line 39, in build_extension '-DPYTHON_LIBRARY=' + get_config_var('LIBDIR'), TypeError: can only concatenate str (not "NoneType") to str.
   Do: Replace setup.py with this file.
3. After successful installation, run the programme and you may report an error: ModuleNotFoundError: No module named 'diffvg'.
   Do: Find diffvg-0.0.1-py3.8-win-amd64.egg in the conda environment folder. Change the inside diffvg file to diffvg.pyd
