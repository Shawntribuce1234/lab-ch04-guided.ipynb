Robust Statistics: Automated Anomaly Detection


Objective

My goal was to explore how different statistical methods identify unusual observations in the California Housing dataset and how summary statistics react when the data is altered.
Methodology
- I analyzed 20,640 observations from the California Housing dataset.
- I calculated the mean, median, trimmed mean, standard deviation, IQR, and MAD.
- I manually implemented Tukey Fences to identify unusual home prices.
- I applied Isolation Forest to detect unusual observations using multiple features.
- I compared the observations identified by Tukey Fences with those identified by Isolation Forest.
- I ran a contamination experiment where 5% of the data was corrupted.
- I compared how the different summary statistics changed after contamination.
Key Findings
Tukey Fences and Isolation Forest identified different observations because Tukey Fences focused on price, while Isolation Forest considered multiple features at the same time. The contamination experiment also showed that some statistics were much less affected by extreme values than others.
