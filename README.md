# HelloWorld API

This is a simple .NET 8.0 API that returns a "Hello World" message.

## Project Structure

- `HelloWorld/` - Contains the source code for the API.
    - `appsettings.json` - Contains the configuration settings for the API.
    - `appsettings.Development.json` - Contains the configuration settings for the API in development environment.
    - `DOCKERFILE` - Contains the Docker configuration for building a Docker image of the API.
    - `HelloWorld.csproj` - The project file.
    - `Program.cs` - The main entry point for the API.
    - `Properties/launchSettings.json` - Contains settings for the project profiles.
    - `obj/` - Contains files that are generated during the build.
- `k8s/` - Contains Kubernetes configuration files.
- `README.md` - This file.

## Running the API

You can run the API using Docker. Build the Docker image by running:

```sh
docker build -t hello-world-api .