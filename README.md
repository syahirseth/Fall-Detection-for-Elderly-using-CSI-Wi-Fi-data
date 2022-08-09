# Fall-Detection-for-Elderly-using-CSI-Wi-Fi-data

Abstract: In recent years, Channel State Information (CSI)  Wi-Fi data has been used more broadly due to deep insight into the physical properties of an environment using radio subcarrier frequencies in orthogonal frequency-division multiplexing (OFDM) systems. Many research studies use this data for motion recognition, pose recognition, and many more. In later years, Intel 5300 and Atheros Wi-Fi cards were widely used to collect the data. In this project, the ESP32 microcontroller was used to collect the CSI data and use it to predict fall and walk movement. ESP32 was chosen for this project because it is lightweight, low-cost, and can work stand-alone compared to Intel 5300 and Atheros, which need to be attached to a laptop to run the program. Two ESP32s were used in this project to act as the receiver and transmitter. Then, Fuzzy Logic and if/else conditions act as the decision maker and predict the movement using the amplitude acquired from the CSI raw data. The research found that the fuzzification and defuzzification showed 97.5% accuracy on the collected data from 20 samples of falls and walks each. 



## Data Collection

This project used [ESP CSI Toolkit](https://stevenmhernandez.github.io/ESP32-CSI-Tool/) created by Hernandez and Bulut to collect CSI raw data. 


## Python code to parse CSI raw data using all 166 lines in a graph

This project used [ESP32 Wi-Fi CSI Python Parser](https://github.com/RikeshMMM/ESP32-CSI-Python-Parser) created by RikeshMMM.

Go to examples -> code -> parse_and_plot_example_csi.ipynb 
