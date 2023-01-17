# turbo-learning

- https://turbo.build/repo/docs/getting-started/existing-monorepo#create-a-pipeline
- https://turbo.build/repo/docs/core-concepts/monorepos/running-tasks
- https://turbo.build/repo/docs/handbook/what-is-a-monorepo#in-a-polyrepo

## Examples

- https://github.com/vercel/turbo/tree/main/examples/with-docker

## Build

```bash
docker build -t web:latest -f ./apps/web/Dockerfile .
docker run --rm web:latest
docker-compose up
```

## Versioning and publishing

- https://github.com/changesets/changesets/blob/main/packages/cli/README.md
- https://github.com/changesets/changesets/blob/main/docs/prereleases.md
