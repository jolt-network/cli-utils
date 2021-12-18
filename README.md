# Jolt CLI utils

This repository contains all the necessary types and utility functions for both `@jolt-network/cli-jobs` and `@jolt-network/cli`.

In this library we can find two important elements:

- A  class (`GanacheFork`) with methods aimed to easily fork a specific network. This allows us to simulate whether a given transaction will be successful, and/or profitable in the chosen network, or not.

- Miscellaneous functions crafted to simplify a variety of tasks like advancing blocks, generating random ids, transforming a string to kebab case, among other useful things.