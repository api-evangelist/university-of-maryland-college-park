---
title: "Running Code Examples Directly from the Site"
url: "https://opendata.lib.umd.edu/posts/2026/09/running-code-examples-directly-from-the-site/"
date: "2026-09-08"
feed_url: "https://opendata.lib.umd.edu/index.xml"
---
The Python code examples on this site are now self-contained. Each script declares its own Python version and dependencies inline, using PEP 723 metadata, so you can run any example directly from this site with a single command, without a checkout or a setup step: uv run https://opendata.lib.umd.edu/code/drum-oaipmh.py This example harvests metadata from DRUM , UMD’s institutional repository. It uses uv , which reads each script’s declared dependencies and runs it in a temporary environment.
