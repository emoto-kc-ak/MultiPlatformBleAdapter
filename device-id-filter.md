# device-id-filter branch

This branch modifies `BleAdapter` so that it can filter device by device addresses when it scans devices.

A library built in this branch is no longer compatible with the original one.

## Building a library

1. Move down to the [`android`](./android) directory.

    ```
    cd android
    ```

2. Run a `build` command with the gradle wrapper.

    ```
    ./gradlew build
    ```

3. You will find a `build` directory created in the [`android/library`](./android/library) directory.

## Packaing

1. Move down to the [`android`](./android) directory.

    ```
    cd android
    ```

2. Run a `publish` command with the gradle wrapper.

    ```
    ./gradlew publish
    ```

3. You will find a `repository` directory created in the [`android`](./android) directory.
   It contains artifacts that can be retrieved via maven with the following keys.
   - group: com.github.emoto-kc-ak
   - name: MultiPlatformBleAdapter
   - version: git commit hash