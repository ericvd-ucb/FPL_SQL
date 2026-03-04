# FPL_SQL
Fantasy Premier League Team Picker

[![Launch in JupyterLite](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://ericvd-ucb.github.io/FPL_SQL)

Run the FPL SQL notebooks directly in your browser — no installation required.

## Overview

This project uses SQL (via [JupySQL](https://jupysql.ploomber.io/)) to analyse Fantasy Premier League player data and help select an optimal squad within the £100m budget.

## Launch

Click the badge above or visit [https://ericvd-ucb.github.io/FPL_SQL](https://ericvd-ucb.github.io/FPL_SQL) to open the interactive JupyterLite environment.

## Local development

```bash
pip install jupyterlite-core jupyterlite-pyodide-kernel
jupyter lite build --contents content --output-dir dist
jupyter lite serve --output-dir dist
```
