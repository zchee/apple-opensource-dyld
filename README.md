```console
$ xcodebuild -sdk macosx11.3 -target dyld_shared_cache_util -configuration Release ARCHS="x86_64" SRCROOT="${PWD}" OBJROOT="${PWD}/build/_obj" SYMRROOT="${PWD}/build/_sym" DSTROOT="${PWD}/build" build
```
