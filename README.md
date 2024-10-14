# RobôAP Client

Fork of [FIRAClient](https://github.com/VSSSLeague/FIRAClient) using CMake as a build system.

## Submodule Initialization

Before building the project, initialize the Git submodule:

```sh
   git submodule update --init --recursive
```

1. Create a build directory:
   ```sh
   mkdir build
   ```

2. Move to the build directory:
   ```sh
   cd build
   ```

3. Configure the project with CMake:
   ```sh
   cmake ..
   ```

4. Build the executable:
   ```sh
   make
   ```

5. Run the client:
   ```sh
   ./roboap-client
   ```

