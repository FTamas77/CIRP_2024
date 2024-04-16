We used data from the European Environment Agency (https://www.eea.europa.eu/en).

**In our case we used this source:** CO2 emissions from new passenger cars registered in EU27, Iceland (from 2018) and Norway (from 2019) – Regulation (EU) 2019/631.

Link to the data: https://co2cars.apps.eea.europa.eu/?source=%7B%22track_total_hits%22%3Atrue%2C%22query%22%3A%7B%22bool%22%3A%7B%22must%22%3A%5B%7B%22constant_score%22%3A%7B%22filter%22%3A%7B%22bool%22%3A%7B%22must%22%3A%5B%7B%22bool%22%3A%7B%22should%22%3A%5B%7B%22term%22%3A%7B%22year%22%3A2019%7D%7D%5D%7D%7D%2C%7B%22bool%22%3A%7B%22should%22%3A%5B%7B%22term%22%3A%7B%22scStatus%22%3A%22Final%22%7D%7D%5D%7D%7D%5D%7D%7D%7D%7D%5D%7D%7D%2C%22display_type%22%3A%22tabular%22%2C%22from%22%3A30%7D

**Note:**

* The source contains more data. When the causal graph was created, we created a complex model, after it, we simplified it. These steps are part of the causal model creation.

* The source file is not added here, because of its size, it is not possible to commit. It can be downloaded using the upper link.
