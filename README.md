# Repository Templates for Bitbucket Server REST OpenAPI Specification

## Links

- Documentation(ReDoc): https://mibexsoftware.github.io/repository-templates-rest-api/


## Working on specification

1. Start a simple http server that watches your files e.g. `npx browser-sync start --server --files "*.html, *.json"`
2. Make changes using your favorite editor or `swagger-editor` (look for URL in console output)
3. All changes are immediately propagated to your local server, moreover all documentation pages will be automagically refreshed in a browser after each change
**TIP:** you can open `swagger-editor`, documentation and `swagger-ui` in parallel
**TIP:** use the redocly extension in VSCode, nice autocompletion and preview functions


### Deployment
1. Merging to master will trigger a Github workflow deploying the latest changes
