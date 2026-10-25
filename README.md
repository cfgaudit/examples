# cfgaudit examples

A small repository that shows where [cfgaudit](https://github.com/cfgaudit/cfgaudit) findings appear. On GitHub, the `cfgaudit` workflow uploads them as SARIF to Code Scanning, so a pull request that adds risky AI-agent configuration gets them as annotations on its lines. On GitLab, the pipeline includes the `cfgaudit-code-quality` component, so a merge request lists them in its Code Quality widget.

The open pull request and merge request add such a configuration on purpose. Do not copy it into a real project.
