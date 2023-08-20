# nasa-mars-scripts
## Scripts/utilities to retrieve information from the NASA site


The directory `bash-curl-python3` contains `bash` scripts that require `curl` and `python3`.
This should work on Linux and Mac OS X.

In theory, just `Python3` should be enough, provided that the user can install necessary modules if they are missing.
You see, we have a `bash` script that invokes `curl` to read a list of images in JSON format,
and invokes `Python3` to parse that JSON. But `python3` can read that list without resorting to `curl`, and definitely
can do what `bash` does.

Nevertheless, these scripts already exist and work.

The directory `python3` contains `python3` scripts.
This should work on Linux, Windows, and Mac OS X (provided that you have the required modules).

## Scripts

`p_urls` - print Perseverance image URLs from a given Sol date.

`c_urls` - print Curiosity image URLs from a given Sol date.


## License

All this stuff is Public Domain.


