# Higgs Boosted Trees Data Information

Higgs data to train a Higgs Boosted Trees SavedModel can be downloaded using the `boosted_trees`
`data_download.py` script.

```
$ pwd
/models/official/boosted_trees

$ export PYTHONPATH=/models/

$ python3 data_download.py
```

In my case, the actual path was `PYTHONPATH=/Users/deroneriksson/Documents/workspace/models/`.
The `data_download.py` script saves the data to `/tmp/higgs_data/HIGGS.csv.gz.npz`.

The HiggsBoostedTreesTest does not use the data file directly for predictions. It uses
the inference example data from `/models/official/boosted_trees/README.md`.
