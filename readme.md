# cmake-configure-build-test-action
GitHub action that configures, builds and tests a CMake project, optionally using emscripten.

### Input Reference
| Input            | Type      | Default Value | Description                                                |
|------------------|-----------|---------------|------------------------------------------------------------|
| `use-emscripten` | `boolean` | `false`       | Sets up the emscripten sdk and configures using `emcmake`. |
| `test`           | `boolean` | `true`        | Enables testing.                                           |