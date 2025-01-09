python_sources(
    name="foo_lib",
    sources=["foo.py"],  # Include only source files
)

adhoc_tool(
    name="my_tool",
    runnable=":foo_lib",
    log_output=True,
    environment="__local_workspace__"
)

run_shell_command(
    name="run_my_tool",
    command="exit 0 ",
    execution_dependencies=[":my_tool"],
)