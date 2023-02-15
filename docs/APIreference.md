# API reference

## Creating activities.json file

??? note "example"
    ### Short example
    ```python
    from locdataMAC.timer import start
    start()
    ```

| Args   | Type | Description | 
|:--------:|:------:|:-------|
| Nothing    | nothing | No argument is requied for start method |

| Returns   |Type | Description | 
|:--------:|:--------:|:-----|
| File    |  activities.json   | After pressing ctrl+c, it should return activities.json file       |


## Generating data.json file

??? note "example"
    ### Short example
    ```python
    from locdataMAC.analytics import json_data
    path = "/Users/sachinmishra/Desktop/check/activities.json"
    json_data(path)
    ```

| Args   | Type | Description | 
|:--------:|:------:|:-------|
| path    | str |input path of activiries.json file |

| Returns   |Type | Description | 
|:--------:|:--------:|:-----|
| File    |  data.json   | return data.json file |


## Generating analytics-chart

??? note "example"
    ### Short example
    ```python
    from locdataMAC.charts import mydata_analysis
    path = "/Users/sachinmishra/Desktop/check/data.json"
    mydata_analysis(path)
    ```

| Args   | Type | Description | 
|:--------:|:------:|:-------|
| path    | str |input path of data.json file |

| Returns   |Type | Description | 
|:--------:|:--------:|:-----|
| Charts    |  2-bar charts  | return 2-bar charts in default- browser |