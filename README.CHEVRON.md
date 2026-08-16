# language-yaml (Chevron)

YAML highlighter for Chevron. Tree-sitter is the default
(`@tree-sitter-grammars/tree-sitter-yaml@0.7.1` via
`grammars/tree-sitter-yaml.json`). The TextMate grammar in
`grammars/yaml.cson` stays as the fallback.

Owned so the pin is not an archived `atom/*` remote.
Chevron loads this via `packageDependencies`.
