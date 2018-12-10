# add_samples
Adds 5 new 2-min code sections to existing eaf files

## add_samples.py

#### usage

```
$ python add_samples.py [input_dir] [output_dir] ACLEW_list_of_corpora.csv
```

where ```input_dir``` is the folder with the original eaf files and ```output_dir``` is where the script will dump the output. the script will also generate a ```selected_regions.csv``` file in the current working directory.

rename selected_regions.csv as selected_regions_XXX.csv where XXX is the three letter corpus name.

### Issues and updates

- [ ] Should be merged with aclew_utils
