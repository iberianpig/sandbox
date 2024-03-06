# Testing Github Actions

install `act` to run Github Actions locally

```sh
$ go install github.com/nektos/act@latest
```

## Running Github Actions locally with `act`

```sh
$ act workflow_dispatch --eventpath .github/workflows/scheduled-job-to-every-2-weeks/biweekly.event
```

```sh
$ act workflow_dispatch --eventpath .github/workflows/scheduled-job-to-every-2-weeks/not-biweekly.event
```
