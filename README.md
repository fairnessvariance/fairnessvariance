# Supplemental materials for "Fairness Variance of Deep Learning  Systems: A Software  Perspective"

## Data for 27 techniques in the paper

Aggregated overall and per-class results for 189 experiments (27 techniques and seven bias metrics) used in the paper: [raw_data.csv](../master/raw_data.csv)

Raw bias numbers for 189 experiments, 16 run per experiment: [raw_bias_numbers](../master/raw_bias_numbers)
* Overall bias: ```./raw_bias_numbers/overall/<Technique>.yaml```. Each yaml file is a dictionary. The key of the dictionary is the bias metric. The value of the dictionary is a list of 16 bias values for each run.
* Per-class bias: ```./raw_bias_numbers/per_class/<Technique>/run_<idx>.yaml```. Each yaml file contains the bias value for all the classes in one run, and is also a dictionary. The key of the dictionary is the bias metric. The value of the dictionary is a list of bias values for each class.
* Statistical test results: [stat_tests.csv](../master/raw_bias_numbers/stat_tests.csv). The csv file contains the results from U-test, Cohen's d number, and Levene's test for 154 experiments (22 mitigation techniques and seven bias metrics).
