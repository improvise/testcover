testcover
=========

Runs all unit tests in files matching (test_*.py) and checks branch coverage

How to use
----------

1. Move test_and_cover to VIRTUALENV_DIR/PROJECT_NAME/bin/DESIRED_NAME
2. Change line 1 to point to your virtualenv Python installation
   (it should match the other python files in the directory.)
3. Change `config_file_loc` to the absolute file directory of your coverage config file.
   (You don't need to do this if you're using the .coveragerc local config file.)
4. While working in the virtualenv, enter DESIRED_NAME to run tests and check coverage.
  No text means you're good!
