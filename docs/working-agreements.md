# Engineering Working Agreements

## Naming Conventions

- Pipelines: PL_<number>_<name>
- Datasets: DS_<source>_<entity>
- Linked Services: LS_<source>
- Databricks notebooks: NB_<layer>_<entity>
- SQL tables: schema_name.table_name
- Python files: snake_case

## Git Conventions

- main: stable branch
- feature/*: development work
- bugfix/*: bug fixes

## Security

- Never commit passwords or API keys.
- Use Azure Key Vault for secrets.
- Use managed identities where supported.
- Keep environment-specific settings separate.

## Development

- Every feature must be committed to Git.
- Add tests for transformation logic.
- Document important architectural decisions.
- Do not hardcode environment-specific paths.