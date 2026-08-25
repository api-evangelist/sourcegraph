---
title: "Filenames are the wrong index for Claude Code @ mentions"
url: "https://sourcegraph.com/blog/claude-code-file-picker-symbol-ranking"
date: "2026-08-20"
author: "Justin Dorfman"
feed_url: "https://sourcegraph.com/blog/rss.xml"
---
Claude Code's @ picker matches characters in a path, so it can't find the file where a function lives. This fileSuggestion hook ranks by symbol instead.
