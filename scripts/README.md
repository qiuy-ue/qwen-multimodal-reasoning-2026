# Public Script Release Boundary

The original V4 archive contains training, data merge, export, and process-guard scripts. The RLX30 materials contain the GRPO training and submission validation workflow.

This public repository does not copy those scripts verbatim because they contain internal paths, private dataset references, and environment-specific assumptions. A future public script release should expose paths as arguments, remove private identifiers, and include a local smoke test.
