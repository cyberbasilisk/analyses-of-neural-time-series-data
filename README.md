# analyses-of-neural-time-series-data
Analysis methods applied to neural / EEG time series data.

An Event Related Potential is a measured brain response that provides evidence of a link between brain electrical activity and a specific stimulus. 
[erp](erp.ipynb) demonstrates extraction of the Event Related Potential using sample data from the [V1 Laminar](v1_laminar.mat) dataset. 

A Static Power Spectra highlights active frequencies in a signal. It gives an idea of which frequency or frequencies are most dominant in the signal. It may also help in identifying some signal artifacts / anomalies. 
[pow_spect](pow_spect.ipynb) demonstrates the extraction of Static Power Spectra using sample data from the [V1 Laminar](v1_laminar.mat) dataset. 

The Event Related Potential highlights information about data in the Time Domain. It allows a researcher to track common features of data across trials and/or channels. The Static Power Spectra allows the identification of feature within data in the frequency domain.

Time-Frequency plots however, present features across both the Time domain and the Frequency domain. A Time-Frequency power plot for instance, will highlight not only the frequencies which exhibit power, but also the time points at which these power bursts occur. There are multiple methods of extracting Time-Frequency information from data.

[time_freq_power_via_freq_mul](time_freq_power_via_freq_mul.ipynb) demonstrates the extraction of Time-Frequency Power via Frequency Domain Multiplication.
