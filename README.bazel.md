# Bazel workflows

This repository uses [Aspect Workflows](https://aspect.build) to provide an excellent Bazel developer experience.

## Installing dev tools

For developers to be able to run additional CLI tools without needing manual installation:

1. Add the tool to `tools/tools.lock.json`
2. Run `bazel run //tools:bazel_env` (following any instructions it prints)
3. When working within the workspace, tools will be available on the PATH

See https://blog.aspect.build/run-tools-installed-by-bazel for details.

