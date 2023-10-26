# Run TimesNet Experiment on Google Colab

A notebook that contains code to reproduce TimesNet experiment of ETTh1 on Google Colab.

# Before uploading the notebook

1. Upload the folder of [Time Series Library](https://github.com/thuml/Time-Series-Library/tree/main) to your Goolge Drive
2. Create a folder called `./dataset` and upload the `ETTh1.csv` from [Time Series Library](https://github.com/thuml/Time-Series-Library/tree/main)
3. Change the notebook environment to GPU 
4. Change line 99 in `run.py` to `args.use_gpu = True` to enforce the use of GPU
5. Upload the notebook to Google Drive (I used absolute path, but feel free to switch to relative path if the notebook is in the same folder as `run.py`)

The notebook contains 4 sections:

- TimesNet Prelim
- TimesNet experiment adapted from [Time Series Library](https://github.com/thuml/Time-Series-Library/tree/main)
- ARIMA model as a basline model (built on [pmdarima](https://github.com/alkaline-ml/pmdarima)
- 5 Metrics to evaluate the performance of both models
