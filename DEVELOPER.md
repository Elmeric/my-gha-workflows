# Developer Notes

Releasing is a totally manual process:

```
$ git checkout main && git pull
$ git tag -a -m "Release v2.0.0" v2.0.0
$ git tag -f -a -m "Release v2.0.0" v2
$ git push -f --tags
```

Once that's done, find the [new tag](https://github.com/Elmeric/my-gha-workflows/tags) and create a GitHub release from it.
