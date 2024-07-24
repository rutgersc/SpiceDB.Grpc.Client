
[![NuGet](https://img.shields.io/nuget/v/SpiceDB.Grpc.Client.svg)](https://nuget.org/packages/SpiceDB.Grpc.Client)

This project contains a dotnet library generated from the [Authzed Protocol Buffers API](https://github.com/authzed/api).

``` bash
# first get the proto files from the submodules
git submodule update --init --recursive --depth 1

# optional: see the currently referenced commits of the submodules
git submodule status

# update submodules to the latest commit
git submodule foreach git pull origin main

# create the new package
dotnet pack

```