# General models

These models were trained using datasets where ants were labelled regardless of their position on the leaf. The models are named with a prefix according to the configuration settings used during the training process and a suffix indicating the model type (centroid or centered_instance).

Models with names that start with "filter_#-stride_#" (where # is a number) were trained with different values for the number of filters and maximum stride, with the specific values indicated in the model name. All other configuration values were kept as the default values with no anchor part.

Models with names that start with "part_*" (where * is the name of a part of the ant skeleton or blank) were trained with different values for the anchor body part, with the specific value indicated in the model name. All other configuration values were kept as the default values.
