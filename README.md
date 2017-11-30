Following is the MT4 Trading platform architecture

![Alt text](/Documents/mt4-architecture.jpg "MetaTrader 4")


**Migrated couple of trading platform data into MT4 trading platform:**
-----------------------------------------------------------------------

**Input:** As a input getting data as CSV file (where all the trading data has been dumped from source trading platform)

**Process:** Design and develop console application with MFC (C++) as MT4 is based on this technology. I have used here MT4 Manager API to control and manage MT4 Application (Client Terminal; Manager Terminal; Administrator). As well as MVC design patter has been used to internally for this application development. There is a configuration file where all the necessary parameters and MT4 trading server credentials are included. Due to security concern configuration file have been removed from source code.

**Output:** Source trading platforms history will have been created into MT4

