# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.
git update-index --chmod=+x entrypoint.sh
git tag -a -m "My first action release" v3
git push --follow-tags

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action
with:
  who-to-greet: 'Mona the Octocat'