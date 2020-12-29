# IATI Decipher

Tool for deciphering IATI organisation files.

## Development

You’ll need `git`, as well as recent versions of `npm`, `node` and `gulp-cli`.

```shell
$ # clone the repo
$ git clone https://github.com/pwyf/iati-decipher.git
$ cd iati-decipher
$
$ # install dependencies
$ npm install
$
$ # watch for changes & create development build
$ npm run watch
```

## Build for distribution

1. First, be sure to bump the version number in `package.json`, `src/static/manifest.json`, and `CHANGELOG.md`.
2. Then run:

   ```shell
   npm run dist
   ```

   This should update the files in the `docs/demo` folder (which are in version control) and create an `extension.zip` file (which isn’t in version control).

3. Commit all changes and push to github
