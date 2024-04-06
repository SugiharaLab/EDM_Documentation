
## <function> ComputeError </function> 
** Description **  :   
Compute Pearson correlation coefficient, maximum absolute error (MAE) and root mean square error (RMSE) between two vectors. A minimum of 5 observation and prediction pairs are required. 

If `nan` are present in `obs` or `pred`, they are removed before computing results. 

** Python **  :   
```python
ComputeError(obs, pred)
```

** R **  :   
```R
ComputeError(obs, pred)
```

---

| Parameter | Type |  Purpose |
| --------- | ---- |  ------- |
| obs       | list |  Observations |
| pred      | list |  Predictions |

<br/>
** Returns **  :   
Dict in `pyEDM`, named List in `rEDM`: with computed `rho`, `RMSE`, `MAE`.
