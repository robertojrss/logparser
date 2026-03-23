# SSH Log Analyzer

[![Python](https://img.shields.io/badge/python-3.6+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/robertojrss/logparser)](https://github.com/robertojrss/logparser/commits)
[![GitHub repo size](https://img.shields.io/github/repo-size/robertojrss/logparser)](https://github.com/robertojrss/logparser)
[![GitHub top language](https://img.shields.io/github/languages/top/robertojrss/logparser)](https://github.com/robertojrss/logparser)
[![Code style](https://img.shields.io/badge/code%20style-pep8-black)](https://www.python.org/dev/peps/pep-0008/)

A powerful SSH authentication log analyzer that detects brute-force attacks, suspicious IPs, and failed login attempts. Helps identify potential security threats in your server logs.

## Features

[![Security](https://img.shields.io/badge/security-log%20analysis-red.svg)](#)
[![Python](https://img.shields.io/badge/python-3.6%2B-blue.svg)](#)
[![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen.svg)](#)

- **Failed password detection** - Identifies all failed authentication attempts
- **Invalid user tracking** - Detects attempts using non-existent usernames
- **IP reputation scoring** - Flags suspicious IPs based on attempt frequency
- **Risk classification** - High (10+ attempts) / Medium (5-9 attempts)
- **JSON report generation** - Structured output with timestamps
- **Top offenders ranking** - Shows IPs with most failed attempts
- **Unique IP extraction** - Complete list of all attacking IPs
- **Simple CLI interface** - Easy to use with any log file

## Installation

[![Clone](https://img.shields.io/badge/clone-https%3A%2F%2Fgithub.com%2Frobertojrss%2Flogparser.git-orange)](https://github.com/robertojrss/logparser.git)

```bash
# Clone the repository
git clone https://github.com/robertojrss/logparser.git

# Navigate to the directory
cd logparser

# No additional dependencies required - uses only Python standard library
