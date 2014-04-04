testcover
=========

Runs all unit tests in files matching `test_*.py` and checks branch code coverage

How to use
----------

1. Move `test_and_cover` to `VIRTUALENV_DIR/PROJECT_NAME/bin/test_and_cover`
2. Change line 1 to point to your virtualenv Python installation
   (it should match the other python files in the directory.)
3. Change `config_file_loc` to the absolute file directory of your coverage
   config file. (You don't need to do this if you're using the `.coveragerc`
   local config file.)
4. While working in the virtualenv, enter `test_and_cover` to run tests
   and check coverage. No text means you're good!

Licensing
---------

This project is licensed under the BSD 3-clause license. (For full text, see 
`LICENSE`).

Basically, you need to provide the `LICENSE` notice somewhere in your project.

I would also appreciate it if you told me about your use of this code, though
this is not required. (Email me at `dev+github@stevenliao.net`)
