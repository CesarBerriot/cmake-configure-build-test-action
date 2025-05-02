# cmake-configure-build-test-workflow
GitHub reusable workflow that configures, builds and tests a CMake project, optionally using emscripten.

### Input Reference
| Input            | Required | Type      | Default Value | Description                                                                                   |
|------------------|:--------:|-----------|---------------|-----------------------------------------------------------------------------------------------|
| `platform`       |    ✔️    | `string`  | `null`        | This input's value is forwarded to the `runs-on` key in the `cmake-configure-build-test` job. |
| `use-emscripten` |    ❌     | `boolean` | `false`       | Sets up the emscripten sdk and configures using `emcmake`.                                    |
| `test`           |    ❌     | `boolean` | `true`        | Enables testing.                                                                              |