# agents-output-styles

This repository holds Claude Code output styles. An output style is a definition file: every line in it shapes how Claude writes.

## Write the artifact, not its provenance

A definition file contains only content that defines behavior.

NEVER add any of the following to a style file unless the human asks for it:

- Attribution, credit, or a "Source" section naming where a rule, a pattern, or an idea came from.
- A link to the repository, article, standard, or tool consulted while writing it.
- A justification borrowed from that source, including a statistic or a claim about why the rule works.
- A note about the edit itself: what it replaces, what changed, or why it was added.
- Commentary addressed to a future reader instead of content that defines behavior.

A definition file defines; it does not cite. When the human needs the provenance, put it in the reply, not in the file.

If a licence genuinely requires attribution in the file, STOP and ask where it belongs. Never decide alone.

## A style obeys itself

A style file is written in the style it defines. Before finishing an edit, read the changed lines against the rules on either side of them. A rule that breaks its own instruction is a defect.
