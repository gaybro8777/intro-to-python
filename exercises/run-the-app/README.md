# "Run the App" Exercise

## Prerequisites

  1. Do the [Version Control Exercise](/exercises/hello-world/version-control.md).
  2. Read up about [Environment Variables](/notes/environment-variables.md), specifically setting via the ".env" file approach.

## Learning Objectives

In this exercise, we'll learn how to install, configure, and run an existing Python application. We'll focus on environment management, package management, and setting environment variables.

## Instructions

  1. Visit the Professor's ["My First Python App" repository](https://github.com/prof-rossetti/my-first-python-app), which contains a simple command-line application. We'll refer to the Professor's repository as the "upstream repository".
  2. Click "Fork" to copy the repo under your own control. We'll refer to your forked copy as the "remote fork", otherwise known as the "origin repository".
  3. Follow the instructions in the repository's "README.md" file to install, setup and run the Python code contained inside:
     1. Use your Git client to "clone" (download) the remote fork onto your local machine, perhaps onto the Desktop. We'll refer to this as the "local repository".
     2. Use the command-line to navigate into the local repository.
     3. Use the `conda` utility to create a new virtual environment with the latest version of Python, then activate it.
     4. Use the `pip` utility to install any required third-party packages specified in the repo's "requirements.txt" file.
     5. Use a ".env" file approach to set an environment variable to customize the user name.
     6. Use the `python` utility to run the Python file(s).

## Success Criteria

Once you have run the app, you will have succeeded. Repeat steps 3.5 and 3.6 (change the environment variable value and re-run the program) at least one more time for good measure.
