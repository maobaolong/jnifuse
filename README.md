## What is JNI-FUSE

A Project which is invented and maintained by alluxio community.

It supply third-party dependency for Alluxio-FUSE.

## How to build

- Full build with native

```shell
$ mvn clean install -PfuseNative
```

- Build java module only without native module

```shell
$ mvn clean install -Djnifuse-native.version=1.0.0
```

## Useful Links

- [Alluxio Website](https://www.alluxio.io/)
- [Documentation](https://www.alluxio.io/docs/)
