# Blade Sample

This is a sample XCode project (single view application) with [Blade](https://github.com/jondot/blade) integrated via a Bladefile.

For more information visit the main [Blade repository](https://github.com/jondot/blade).




## Getting started:

```
$ brew tap jondot/tap
$ brew install blade
$ git clone https://github.com/jondot/blade-sample
$ cd blade-sample
$ blade --verbose
```


If you don't want to install, check out the walk-through here:

![walkthrough](blade-walkthrough.gif)


## Using XCode build step to pregenerate images on build

You can add blade as a build step. To take that version of the sample, checkout the `with_buildstep` branch:

```
$ git checkout with_buildstep
```

Now open the project in XCode, delete the appicons (just for testing) and build it. The icons will magically re-appear.


Thanks!

