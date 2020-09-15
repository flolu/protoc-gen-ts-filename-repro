Dots in filenames seem to cause errors.

## Setup

```
yarn install
yarn build
```

throws:

```
ERROR: /home/flolu/Desktop/protoc-gen-ts-filename-repro/BUILD.bazel:23:17: output 'other.message.ts' was not created
ERROR: /home/flolu/Desktop/protoc-gen-ts-filename-repro/BUILD.bazel:23:17: not all outputs were created or valid
```
