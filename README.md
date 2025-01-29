This Python script is designed to identify and flag FedNow and Real-Time Payment (RTP) customers within the Federal ACH Directory. Additionally, it exports any unidentified routing numbers to separate CSV files. The long-term goal of this project was to visualize all FedNow and RTP customers on an interactive map, highlighting potential customers whose competitors are already using instant payment services. If you have any questions or comments about this repository, or would like to contact me about possible opportunities, please email kayleigh.soukup@gmail.com.

Process Steps:

1. Data Collection (all necessary CSVs for testing are in the zip folder labeled "Dependable CSVs")

        - Updated FedNow and RTP participant routing numbers.

        - The most recent bank and credit union branch location information.

        - The most recent Federal ACH Directory.

2. Data Preparation
    a. Flagging
        - Ensure that all CSV files are in the same folder location as the python file (FedNow_RTP_Customers.ipynb).

        - Open notebook, ensure the CSV names match the appropriate file names within the python script, then 
            run all cells in order to clean the data and flag FedNow and RTP
            participants within the Federal ACH Directory.

        - Routing numbers will be used to mark in separate columns whether an
            institution is a FedNow participant, an RTP participant, or both (1=yes, 0=no).

        - Python code in the ipynb file will also take routing numbers that have yet
            to be identified and collect them in a separate dataset to be saved.

