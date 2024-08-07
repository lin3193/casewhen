# casewhen
對於結果可以利用case when方式，類似if else的方式進行資料細部處理
```
declare @isNagative bit = 1
declare @amount decimal(18,2) = 500.5
select @amount * (case when @isNagative = 1 then -1 else 1 end) as result
```
