# MSBuild Projects

* This repository contains sample MSBuild Projects.

## MSBuild Commands

```cmd
> MSBuild.exe property.proj
> MSBuild.exe build.proj /verbosity:quiet /p:Environment=PreProduction /p:AllowedReferenceRelatedFileExtensions=none
> MSBuild.exe build.proj /verbosity:quiet /p:Environment=Production /p:AllowedReferenceRelatedFileExtensions=none
```

## TODO

* [Copy the newer source file](https://stackoverflow.com/questions/19665232/make-an-msbuild-copy-task-only-copy-if-the-source-is-newer-regardless-of-size)
