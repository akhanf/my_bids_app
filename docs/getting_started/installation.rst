Installation
============

My BIDS App


Install from github:

```
pip install -e http://github.com/akhanf/my_bids_app
```


Running the app
===============

Do a dry-run first (`-n`) and simply print (`-p`) what would be run:

```
my_bids_app /path/to/bids/dir /path/to/output/dir participant -np
```

Run the app, using all cores:

```
my_bids_app /path/to/bids/dir /path/to/output/dir participant --cores all
```

If any workflow rules require containers, then run with the `--use-singularity`` option.




