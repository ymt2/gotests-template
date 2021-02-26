# gotests-template

Templates for [github.com/cweill/gotests](https://github.com/cweill/gotests). 

## Features

- Use [github.com/google/go-cmp/cmp](https://godoc.org/github.com/google/go-cmp/cmp) instead of reflect.DeepEqual
- Use map to manage test case instead of slice
- Make tests run in parallel

## How to use

Set a `GOTESTS_TEMPLATE_DIR` environment variable.
