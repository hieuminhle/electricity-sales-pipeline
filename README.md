<center><img src="resources/energy_department.png" width=500></center>
<p>

The task is to automate the process of retrieving and cleaning data by building a data pipeline to pull data each month, in order to observe changes in the sales and capability of different energy types.

Two raw files; `electricity_sales.csv` and `electricity_capability_nested.json`.

Below is a data dictionary for the `electricity_sales.csv` dataset, which data are transformed in.

| Field            | Data Type |
| :--------------- | :-------: |
| period           |   `str`   |
| stateid          |   `str`   |
| stateDescription |   `str`   |
| sectorid         |   `str`   |
| sectorName       |   `str`   |
| price            |  `float`  |
| price-units      |   `str`   |
