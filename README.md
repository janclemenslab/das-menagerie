# Model menagerie for _DAS_
See [_DAS_](https://github.com/janclemenslab/das).


## Models

| Name    |Species                                            | Song types                   | Channels | Samplerate (kHz)| URL   | Reference |
|----------|--------------------------------------------------|-----------------------------|---------|----------------|-------|----------|
| Dmel_single_v1.0 | [_Drosophila melanogaster_](dmel_single/demo.ipynb) | Male pulse and sine          | 1       | 10.0          |       |         |
| Dmel_multi_v1.0  | [_Drosophila melanogaster_](dmel_single/demo.ipynb)| Male pulse and sine (two networks) | 9       | 10.0          |       |         |
| mouse_v1.0  | [Mouse](mouse/demo.ipynb)                       | Female and male USVs        | 1       | 300.0          |       |         |
| BF_S_1  |Bengalese finch                                     | 48 syllables from 4 males    | 1       | 32.0          |       |         |
| ZF_S_1  |Zebra finch                                         | 6 syllables from main motif  | 1       | 32.0          |       |         |
| marmost_v1.0  | [Marmoset](marmoset/demo.ipynb)                  | Ek, Trill, Tsik, Twitter       | 1       | 44.1          |       |         |


## TODO
- how to handle model and data files? maybe create a release for each model?
- need to version models!!


## API:
- `x, y_true, samplerate_Hz = das.trained_models.MODELNAME.load_data()`
- `model, params = das.models.trained_MODELNAME.load_model_and_params()`
- `das.trained_models`
