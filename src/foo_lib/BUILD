python_sources(
    name="foo_lib",
    sources=["foo.py"],  # Include only source files
)

python_tests(
    name="foo_lib_tests",
    dependencies=[":foo_lib"],  # Test depends on the library
    sources=["test_foo.py"],    # Include only test files
)