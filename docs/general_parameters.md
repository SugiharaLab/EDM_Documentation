# General Parameters

Many of the EDM functions use the same prediction engine, 
and so they share many of the following parameters. 
Please refer to the documentation according to the specific function
to verify which parameters are applicable as well as the default values 
(which can change from function to function).

| Parameter | Type | Default | Purpose |
| --------- | ---- | ------- | ------- |
| pathIn    | string | "./"  | Input data file path | 
| dataFile  | string | ""    | Data file name | 
| dataFrame | pyEDM: Pandas DataFrame, rEDM: data.frame | None |Input DataFrame| 
| pathOut   | string | "./"  | Output file path | 
| predictFile | string | ""  | Prediction output file | 
| lib       | string | ""    | [library start index : library stop index] | 
| pred      | string | ""    | [prediction start index : prediction stop index] | 
| E         | int    | 0     | Data dimension | 
| Tp        | int    | 0     | Prediction Interval | 
| knn       | int    | 0     | Number nearest neighbors | 
| tau       | int    | 1     | Embedding delay | 
| theta     | int    | 0     | SMap localization | 
| exclusionRadius | int | 0  | Prediction vector exclusion radius | 
| columns   | string | ""    | Column names or indices for prediction | 
| target    | string | ""    | Target library column name or index |
| embedded  | bool   | False | Is data an embedding |
| const_pred| bool   | False | Include non projected forecast data |
| verbose   | bool   | False | Echo messages |
| smapFile  | string | ""    | SMap coefficient output file |
| libSizes_str | string | "" | CCM library sizes |
| sample    | int    | 0     | CCM number of random samples |
| random    | bool   | True  | CCM use random samples? |
| seed      | unsigned | 0   | RNG seed, 0 = random seed |

