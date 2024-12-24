# Dockerfile Bug: Missing File in CMD

This repository demonstrates a common Dockerfile error where the `CMD` instruction references a file that is not included in the build context.

The original `Dockerfile` attempts to run `main.py`, but this file is missing from the image build context. This leads to a build failure.

The solution `DockerfileFix` provides the correct way to include the `main.py` file and fix the error.