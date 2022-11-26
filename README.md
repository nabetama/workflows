# workflows
Stock actions.

## Usage

```yaml
name: test

on:
  pull_request:
  push:
    branches:
      - main

jobs:
  test:
    uses: nabetama/workflows/.github/workflows/tag.yml@main
    
```
