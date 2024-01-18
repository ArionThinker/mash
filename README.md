# [ArionThinker/mash](https://mash.pkgx.sh/u/ArionThinker/)

## `mash pantry checker`

This is a small script that checks which packages are missing in the pkgx pantry compared to Homebrew.

### Details

The script gets a list of popular packages in Homebrew and displays us which of them is missing in PKGX.
We can change the search criteria (days|count of installs) as well as write the result in the file.

### Usage

This will show us popular packages in 365 days that have been installed at least 100,000 times:
```sh
$ mash pantry checker
```

Or we can display the `list.txt` file results in 90 days with at least 10000 installations:
```sh
$ mash pantry checker -d 90 -m 10000 -o list.txt
```

Or get help:
```sh
$ mash pantry checker -h
```

&nbsp;
