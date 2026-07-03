# ALX System Engineering & DevOps

Shell scripting and system engineering projects, built as part of the [ALX Software Engineering](https://www.alxafrica.com/) curriculum. Each directory is a self-contained module focused on a specific Unix/Linux system engineering skill, moving from basic shell usage up to networking fundamentals.

## About

This repository documents my progression through core system engineering concepts: writing shell scripts, managing permissions, handling I/O redirection, working with variables, controlling program flow, managing processes and signals, using regular expressions, and understanding networking basics. All scripts are written in Bash and follow the Shellcheck / Betty style conventions used throughout the ALX curriculum.

## Repository structure

| Directory | Topic | What it covers |
|---|---|---|
| [0x00-shell_basics](./0x00-shell_basics) | Shell Basics | Navigating the filesystem, running commands, the shebang line, absolute vs. relative paths |
| [0x01-shell_permissions](./0x01-shell_permissions) | Permissions | File/directory permissions, `chmod`, `chown`, `chgrp`, ownership, and the Unix permission model |
| [0x02-shell_redirections](./0x02-shell_redirections) | Redirections | Standard input/output/error, `>`, `>>`, `<`, pipes, and combining commands |
| [0x03-shell_variables_expansions](./0x03-shell_variables_expansions) | Variables & Expansions | Environment vs. local variables, command substitution, arithmetic expansion, special variables |
| [0x04-loops_conditions_and_parsing](./0x04-loops_conditions_and_parsing) | Loops, Conditions & Parsing | `if`/`else`, `case`, `for`/`while`/`until` loops, `cut` and text parsing |
| [0x05-processes_and_signals](./0x05-processes_and_signals) | Processes & Signals | Process states, `ps`, `kill`, trapping signals, foreground/background jobs |
| [0x06-regular_expressions](./0x06-regular_expressions) | Regular Expressions | `sed`, basic and extended regex, pattern matching and text substitution |
| [0x07-networking_basics](./0x07-networking_basics) | Networking Basics | The OSI model, `ifconfig`/`ip`, DNS, `/etc/hosts`, ports, and basic connectivity |

Each folder contains the individual task scripts along with any task-specific notes.

## Requirements

- A Unix-like environment (Ubuntu 20.04 LTS or later recommended)
- Bash (scripts start with `#!/usr/bin/env bash` or `#!/bin/bash`)
- Scripts are written to pass [Shellcheck](https://www.shellcheck.net/) with no warnings
- All files end with a newline and follow the Betty shell style guide

## Usage

Clone the repository and run any script directly:

```bash
git clone https://github.com/Anthony4pf/alx-system_engineering-devops.git
cd alx-system_engineering-devops/0x00-shell_basics
chmod +x 0-*
./0-*
```

## Author

**Anthony** ([@Anthony4pf](https://github.com/Anthony4pf))

## Acknowledgments

Projects and task specifications from the [ALX Software Engineering](https://www.alxafrica.com/) program.
