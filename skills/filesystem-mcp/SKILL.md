---
name: filesystem-mcp
description: This skill should be used when manipulating files and directories. Activates for reading and writing files, extracting file paths, and searching files.
---

## When to Use This Skill
- Use Filesystem MCP for:
  - listing directories
  - reading files
  - searching files by name/path
  - getting file metadata
  - creating directories
  - creating/writing/editing/moving files
- Treat Filesystem MCP as the **default and first choice** for file operations.

## Use shell only when necessary
- Use `bash` only for true terminal/runtime tasks (e.g., `git`, `npm`, `bun`, `python`, tests, builds, process execution).
- Do **not** use shell file-manipulation commands (`cat`, `ls`, `find`, `grep`, `sed`, `awk`, `mv`, `cp`, `mkdir`, `rm`, etc.) when an equivalent Filesystem MCP operation exists.

## Exception rule
- If Filesystem MCP cannot perform the task (capability gap, path restriction, or tool error), briefly state why and then use the minimal shell fallback needed.