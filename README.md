# npm-install-action

## How to use

```
jobs:
  install:
    runs-on: ubuntu-latest

    steps:
      - name: Check-out
        uses: actions/checkout@v3
        with:
          fetch-depth: 1

      - name: Npm install
        uses: wintero92/npm-install-action@v1
```

## Inputs

See `action.yaml` for possible inputs.