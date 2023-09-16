# HumanCat Action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `human-name`

**Required** The name of the human. Default `"Ryan"`.

### `cat-name`

**Required** The name of the cat. Default `"Cat"`.

## Outputs

### `human-name`

The name of the human

### `human-age`

The age of the human

### `cat-name`

The name of the cat

### `cat-status`

The status of the cat

## Example usage

```yaml
uses: jihyungSong/humancat@v1.0
with:
  human-name: 'Leo'
  cat-name: 'Nabi'
```

