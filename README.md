In this project, we explore the application of the Dual-Stage Attention-Based Recurrent Neural Network (DA-RNN) [1] to predict precipitation levels using the ERA5 dataset  [2]. The DA-RNN architecture is specifically designed to address two major limitations of classical time series models: (i) their inability to select the most relevant input features, and (ii) their weakness in capturing long-range temporal dependencies, which are critical for modeling complex weather patterns.

The DA-RNN model has already demonstrated state-of-the-art performance on financial (NASDAQ 100 Stock dataset) and environmental datasets (SML 2010 dataset) by capturing long-term dependencies and filtering relevant features through input and temporal attention mechanisms. Thus, this makes DA-RNN suitable for multi-variate, exogenous time series data such as ERA5, where the goal is to predict a target variable (precipitation) based on multiple atmospheric drivers.

For methodology & results, please refer to the Report.

References:

[1] Qin, Y., Song, D., Chen, H., Cheng, W., Jiang, G., & Cottrell, G. (2017). A Dual-Stage Attention-Based Recurrent Neural Network for Time Series Prediction. arXiv preprint arXiv:1704.02971. https://arxiv.org/pdf/1704.02971
[2] ERA5 Climate Reanalysis Dataset. Copernicus Climate Data Store. https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels?tab=overview
