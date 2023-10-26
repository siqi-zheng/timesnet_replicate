# TimesNet Replication on Google Colab

Source code to reproduce TimesNet Experiment on Google Colab.

# Before uploading the notebook

1. Upload the folder of [Time Series Library](https://github.com/thuml/Time-Series-Library/tree/main) to your Goolge Drive
2. Change the notebook environment to GPU 
3. Change line 99 in `run.py` to `args.use_gpu = True` to enforce the use of GPU
4. Upload the notebook to Google Drive (I used absolute path, but feel free to switch to relative path if the notebook is in the same folder as `run.py`

The notebook contains 4 sections:

- TimesNet Prelim
- TimesNet experiment adapted from [Time Series Library](https://github.com/thuml/Time-Series-Library/tree/main)
- ARIMA model as a basline model (built on [pmdarima](https://github.com/alkaline-ml/pmdarima)
- 5 Metrics to evaluate the performance of both models
