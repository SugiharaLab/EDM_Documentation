
## <function> ComputeError </function> 
**Description**  :   
Compute Pearson correlation coefficient (rho), maximum absolute error (MAE), cumulative absolute error (CAE) and root mean square error (RMSE) between two vectors. A minimum of 5 observation and prediction pairs are required. 

If `nan` are present in `obs` or `pred`, they are removed before computing results. 

**Python**  :   
```python
ComputeError(obs, pred)
```

**R**  :   
```R
ComputeError(obs, pred)
```

---

| Parameter | Type |  Purpose |
| --------- | ---- |  ------- |
| obs       | vector | Observations |
| pred      | vector | Predictions  |

<br/>
**Returns**  :   
`pyEDM`: dictionary with computed `rho`, `RMSE`, `MAE`, `CAE`<br>
`rEDM`: named list with computed `rho`, `RMSE`, `MAE` 
