# Project1 — Lightweight Repository & Codebase Analyzer

A fast, zero-dependency command-line tool that scans local software repositories to analyze file distribution, line counts, TODO/FIXME technical debt markers, and project health metrics.

## Features
- **Language & File Breakdown:** Instantly counts files and lines of code across extensions.
- **Technical Debt Scanner:** Flags `TODO`, `FIXME`, and `BUG` comments with file names and line numbers.
- **Zero External Dependencies:** Built entirely with the Python 3 standard library for instant setup.

## Installation

```bash
git clone https://github.com
cd Project1
```

## Usage

Run the analyzer on any local directory:

```bash
python3 analyzer.py /path/to/your/repo
```

### Example Output
```text
Scanning repository: ./my-app
----------------------------------------
Total Files Scanned : 24
Total Lines of Code : 3,412
Technical Debt Tags : 4 found

File Breakdown:
  .py   : 14 files (2,150 lines)
  .md   : 3 files (410 lines)
  .json : 7 files (852 lines)

Flagged Comments:
  [TODO] src/api.py:42 -> Add rate-limiting middleware
  [FIXME] src/auth.py:89 -> Handle expired refresh tokens
```

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com).

## License
Distributed under the MIT License. See `LICENSE` for more information.
# Project1
