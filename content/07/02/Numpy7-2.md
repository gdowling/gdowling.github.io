---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.2'
      jupytext_version: 1.3.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---

<!-- #region -->
<a id="numpy_performing_stats_math"></a>
## __Peforming Stats and Math__

You can use NumPy methods to perform descriptive statistics and mathematical operations on NumPy arrays. You can also perform many of these same operations on ```pandas``` dataframes. For more complex mathematical opertions refer the [```SciPy```](https://docs.scipy.org/doc/scipy/reference/tutorial/general.html) library.

<a id="numpy_performing_stats_math_stats"></a>
   __Stats:__

   - [```np.mean(array,axis=0)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.mean.html?highlight=mean#numpy.mean) will return mean along specific axis (0 or 1)
   - [```sum```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.sum.html?highlight=sum#numpy.sum) will return the sum of the array
   - [```min(axis=0)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.ndarray.min.html) will return the minimum value of the array
   - [```max(axis=0)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.ndarray.max.html?highlight=max#numpy.ndarray.max) will return the maximum value of specific axis
   - [```np.var(array)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.var.html?highlight=var#numpy.var) will return the variance of the array
   - [```np.std(array,axis=1)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.std.html?highlight=std#numpy.std) will return the standard deviation of specific axis
   - [```corrcoef```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.corrcoef.html?highlight=corrcoef#numpy.corrcoef) will return the correlation coefficient of the array
   - [```np.median(array)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.median.html?highlight=median) will return the median of the array elements

<a id="numpy_performing_stats_math_math"></a>
__Math:__

   - [```np.add(array ,1)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.add.html?highlight=add#numpy.add) will add 1 to each element in the array
   - [```np.add(array1,array2)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.add.html?highlight=add#numpy.add) will add array 2 to array 1. 
   - The same is true to [```np.subtract```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.subtract.html?highlight=subtract#numpy.subtract), [```np.multiply()```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.multiply.html?highlight=multiply), [```np.divide()```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.divide.html?highlight=divide#numpy.divide) and [```np.power()```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.power.html?highlight=power) all these commands would work in exactly the same way as described above.

   _You can also get NumPy to return different values from the array, below are a few examples:_
    
    
   - [```np.sqrt(array)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.sqrt.html?highlight=sqrt#numpy.sqrt) will return the square root of each element in the array
   - [```np.sin(array)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.sin.html?highlight=sin#numpy.sin) will return the sine of each element in the array
   - [```np.log(array)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.log.html?highlight=log#numpy.log) will return the natural log of each element in the array
   - [```np.abs(array)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.absolute.html?highlight=abs#numpy.absolute) will return the absolute value of each element in the array
   - [```np.array_equal(arr1,arr2)```](https://docs.scipy.org/doc/numpy/reference/generated/numpy.array_equal.html?highlight=array_equal#numpy.array_equal) will return True if the arrays have the same elements and shape
<!-- #endregion -->
