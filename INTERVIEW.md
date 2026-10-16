# HRMS application — fork: reviewer guide

An inherited application source tree organized into backend and frontend directories.

## Start the review

Identify the upstream application and show your own commit diff before claiming implementation ownership.

| Source | Review focus |\n| --- | --- |\n| [backend](backend) | Implementation, assumptions, and operational boundaries |\n| [file.txt](file.txt) | Implementation, assumptions, and operational boundaries |\n| [frontend](frontend) | Implementation, assumptions, and operational boundaries |

## A useful interview walkthrough

1. State the problem and the specific part you implemented or changed.
2. Open the source above and follow one request, release, or failure from start to finish.
3. Show a reproducible result, including an actual failure and the observation that confirms recovery.
4. Explain one tradeoff and one limitation. Distinguish a local test from a live deployment.

## Evidence and limits

This guide is based on the default-branch source inspected on 16 October 2026. It is a source review, not a fresh deployment or a certification of every feature. Existing CI runs and tests should be checked at the commit being demonstrated. Do not present screenshots, inherited code, planned features, or old README statements as proof of a current deployment.

## Attribution

This repository is a fork of [shubham93096/new-hrms-sourcecode](https://github.com/shubham93096/new-hrms-sourcecode). The application and existing documentation retain their original authorship. Use commit diffs to identify any changes made in this fork; no original authorship or completed deployment is implied.
