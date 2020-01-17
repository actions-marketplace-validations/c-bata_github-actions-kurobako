# github-actions-kurobako

GitHub Action to report kurobako benchmark results on the PR.

## Inputs

### `report-json-path`

**Required** File path to a json generated by kurobako run command. Default `"/home/runner/kurobako.json"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: c-bata/github-actions-kurobako@master
with:
  report-json-path: '/home/runner/kurobako-report.json'
```