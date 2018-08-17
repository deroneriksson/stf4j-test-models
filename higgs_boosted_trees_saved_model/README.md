# Higgs Boosted Trees SavedModel Information

This directory contains a TensorFlow Higgs Boosted Trees SavedModel.

To train a new Higgs Boosted Trees model and save as SavedModel.

```
$ pwd
/models/official/boosted_trees

$ export PYTHONPATH=/models/

$ python3 data_download.py

$ python3 train_higgs.py --export_dir /higgs_boosted_trees_saved_model
```

In my case, the actual path was `PYTHONPATH=/Users/deroneriksson/Documents/workspace/models/`.
