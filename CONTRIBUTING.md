# Contributing your own model

- Open a [pull request](https://github.com/janclemenslab/das-menagerie/pulls).
- Each model is in a directory with an informative name and the following files:
    - `README.md` (indicate DAS version), details on training data (source etc., ideally link to `npy` dir) (REQUIRED)
    - `model` - directory with the model and the params file (REQUIRED).
    - `data.ext` - file or directory with test data. Ideally with groundtruth annotations for testing the model (OPTIONAL)
    - `demo.ipynb` - load the data, run model with test data and post process, visualize predictions, and compare predictions to groundtruth. (OPTIONAL)
- Upon acceptance, we will add an entry for your model to the table in the repo's top-level `README.md`.