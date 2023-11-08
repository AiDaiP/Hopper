# Examples for Hopper

We have set configurations in `hopper.config` files for the examples. You can install the libraries and change the path for the header and shared libraries in your environment.

If `hopper` detects the configuration file in current directory, it loads the setting. Therefore, you can run `hopper` directly by following commands.

``` sh
# compile fuzzer for library
hopper compile 
# run fuzzer
hopper fuzz
# translate specific file
hopper translate 
# clean files generated by fuzzing to restart from scratch
hopper clean
# sanitize crashes
hopper sanitize
```