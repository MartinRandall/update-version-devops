# Updates Version
 
Powershell script to update the version of a build as part of the build process. It will extract the version number from the build name as #.#.#.# (4 numbers), i.e. My Build 1.2.3.4 -> version is 1.2.3.4. This version is updated in the .csproj files PackageVersion settings.