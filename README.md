# Secret CLI

This workshop will have you make a CLI tool for holding all your secrets.
It will be a simple tool that will allow you to store and retrieve secrets from a file.
The file will be encrypted using a password that you provide.

## Credits

Thanks to [San Diego Gophers](https://github.com/SDGophers/secret) for this idea.

## Requirements

- [Go](https://go.dev/dl/)

## Goals

- [ ] Create a CLI tool that can store and retrieve secrets
- [ ] The secrets should be stored in a file

The output should be something like;
```
$ secret set twitter_api_key "some value here" -k="your-encoding-key"
# Value set!
$ secret get twitter_api_key -k="your-encoding-key"
# "some value here"
```

## Help

You can find help in the tips section, careful opening it though, there may be spoiler ideas in the file names.