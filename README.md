# JSPM error when importing crypto

The native `crypto` is not found when requiring it.
Here, this error breaks a build with `reflect-metadata` because this package relies on `crypto`.

Execute the build with:
````bash
jspm bundle-sfx index dist/index
````
