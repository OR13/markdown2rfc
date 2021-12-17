# or13/markdown2rfc

Based on [oauthstuff/markdown2rfc](https://github.com/oauthstuff/markdown2rfc).

### Build Image

Build and tag the docker image.

```
docker build -t or13/markdown2rfc ./docker
```

### Build Spec

Build the spec and place it in the `build` folder.

```
./spec/build.sh
```

### Clean

Remove all local built assets.

```
./spec/clean.sh
```
