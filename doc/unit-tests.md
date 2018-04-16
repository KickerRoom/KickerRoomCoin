Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the kickerroomd tests manually, launch `src/test/test_kickerroom`.

To add more kickerroomd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the kickerroom-qt tests manually, launch `src/qt/test/test_kickerroom-qt`

To add more kickerroom-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
