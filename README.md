# v8-android-bin
The binary version of V8 JavaScript engine built for Android.
The repository created to simplify TPS process.

Master and version tag branches should never have binaries committed because TPS tool will put the binary into the git repository which we want to avoid.
`tag-bin` branch will have binary artifacts and could be used by third-parties.

We will commit the binaries to git-lfs once TPS git clone is completed.

