
## Set-up
- Create conda environment
    ```sh
    conda create -n "pytorch" python=3.9.6
    conda install pytorch torchvision torchaudio cpuonly -c pytorch
    conda install anaconda::ipykernel
    conda install anaconda::pandas
    conda install anaconda::scikit-learn
    conda install anaconda::statsmodels
    conda install conda-forge::pmdarima
    conda install anaconda::seaborn
    conda install -c conda-forge torchinfo
    ```
- Activate conda environment
    ```sh
    conda activate pytorch
    ```

## Resources
- https://medium.com/@krzysztofdrelczuk/acf-autocorrelation-function-simple-explanation-with-python-example-492484c32711
- https://medium.com/@jihyun.kim423/exploring-the-seasonal-arima-sarima-model-for-forecasting-differences-from-arima-e30c3488e5f6
- https://www.kaggle.com/code/jurk06/auto-arima-on-multivariate-time-series
- https://github.com/husnejahan/Multivariate-Time-series-Analysis-using-LSTM-ARIMA/blob/master/air_quality_multivariate-var%20model.ipynb
- https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/
- https://www.datacamp.com/tutorial/arima
- https://analyticsindiamag.com/ai-mysteries/quick-way-to-find-p-d-and-q-values-for-arima/
