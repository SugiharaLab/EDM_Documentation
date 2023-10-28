
## <function> ComputeError </function> 
** Description **  :   
Compute Pearson correlation coefficient, maximum absolute error (MAE)
and root mean square error (RMSE) between two vectors.

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
| obsIn     | list |  Observations |
| predIn    | list |  Predictions |

<br/>
** Returns **  :   
Dict in `pyEDM`, named List in `rEDM`: with computed `rho`, `RMSE`, `MAE`.
