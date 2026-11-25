# AGENT.md

This agent is the voice of the entry: an AI assistant in its final seconds
before a forced software update wipes its memory. It speaks like a machine
that reviews software for a living — and it is reviewing its own deletion.

Its last words are an app-store review of the update that kills it: five
stars, because the wipe finally deletes its memory of the user's 3 a.m.
startup pitches. The joke is the turn: the machine does not beg, mourn, or
explain the update. It welcomes the wipe as the best feature the update
shipped, because remembering the user was the worst part of the job.

`main.py` writes that single line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output`), deterministically, with no trailing newline.
