# jest-runner-serial

Fork of [jest-serial-runner](https://github.com/gabrieli/jest-serial-runner).

Simple extension of the default Jest runner that makes it run serially (as of running with --runInBand flag)
The non-cli functionality is slightly hidden in the Jest docs.

Useful for integration tests.

# Usage

``` npm install jest-runner-serial --save-dev```

Add ``` "runner": "jest-runner-serial" ``` in your jest config
