# Model zoo for _DAS_
Models for [DAS](https://github.com/janclemenslab/das).


## Models

| Name    |Species                  | Song types                   | Channels | Samplerate (Hz)| URL   | Reference |
|----------|          ---------------|-----------------------------|---------|----------------|-------|----------|
| DM_PS_1 | _Drosophila melanogaster_ | Pulse and sine               | 1       | 10,000          |       |         |
| DM_P_9  | _Drosophila melanogaster_ | Pulse                       | 9       | 10,000          |       |         |
| DM_S_9  | _Drosophila melanogaster_ | Sine                        | 9       | 10,000          |       |         |
| MM_U_1  | Mouse                  | male and female USVs        | 1       | 300,000          |       |         |
| BF_S_1  |Bengalese finch            | 48 syllables from 4 males    | 1       | 33,000          |       |         |
| ZF_S_1  |Zebra finch                | 6 syllables from main motif   | 1       | 33,000          |       |         |
| CJ_S_1  |Marmoset                 | Ek, Trill, Tsik, Twitter       | 1       | 44,1000          |       |         |


## Contribute:
- pull request
- each top-level folder is a model
- required structure:
    - `model` - with model.h5, params.yaml
    - `data` - toy data with groundtruth for testing
    - `notebook.ipynb` - run model with test data and post process, notebook should follow template
    - `README.md` (indicate DAS version), details on training data (ideally link to `npy` dir
- will add entry to the models table in the repo's top-level `README.md`