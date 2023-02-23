---
share: true
---
## 3.2  使用 filter ()筛选行
```R
filter(flights, month == 1, day == 1)
```
filter 就是可以通过它来筛选出你想要的航班

比较运算符： > >- < <= != ==

## 使用 arrange () 排列行
arrange ( )函数的工作方式与 filter（）类似，但 arrange 是直接去改变顺序了。
比如
```R
arrange(flights, year, month ,day)
```
就是说按照所有的 flights 按照 year month day 的顺序排列，其他的类别是继续。
>使用 desc（）可以按列进行降序排列

