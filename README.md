# gh-actions-docker

This action prints "Hello World" or "Hello" + the name of the person to greet to the log.

## Inputs

### `who-to-greet`

**Requried** The name of the person to greet. Default `World`.

## Ouputs

### `time`

The time we greeted you.

## Example usage

```
uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: Mona the Octocat
```
