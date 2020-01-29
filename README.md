#wiremock-pcf

This repo contains a working example showing how to run the standalone Wiremock server with custom `mappings`. It implements the `Dist Zip Container` method using Java buildpack, as described in the link below.

<https://github.com/cloudfoundry/java-buildpack/blob/master/docs/container-dist_zip.md>

## Run
In order to run the sample app, make sure you are logged into PCF then run the following commands:

```
$ git clone https://github.com/ykpivot/wiremock-pcf.git
$ cd wiremock-pcf
$ cf push
```

Then open your favorite browser and go to the following address:

<http://wiremock-test.your.pcf.foundation.com/greeting/hello>

That's it!


