Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the somniod tests manually, launch src/test/test_somnio .

To add more somniod tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the somnio-qt tests manually, launch src/qt/test/somnio-qt_test

To add more somnio-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
