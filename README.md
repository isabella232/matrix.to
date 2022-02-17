# Matrix.to for chat.a8c.com
Customised version of [matrix.to](https://github.com/matrix-org/matrix.to) for [Automattic/chat.a8c.com](https://github.com/Automattic/chat.a8c.com).

## Issuing a new release
You can trigger the [creation of a new release](https://github.com/Automattic/matrix.to/actions/workflows/release.yml) by adding a new tag and pushing it. The version number should be the [upstream version](), with an extra "decimal", which represents our own internal sub-version. Find our [latest version](https://github.com/Automattic/matrix.to/releases/latest), increment by one, then create and push the tag:

```shell

git tag -a 1.2.3.4

# Enter a descriptive message for the tag.
# This message will be used as the release's description.

git push --tags
```

## Running locally

1. Install [yarn](https://classic.yarnpkg.com/en/docs/install)
1. `yarn`
1. `yarn start`
1. Go to http://localhost:5000 in your browser
