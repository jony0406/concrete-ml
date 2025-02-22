<!-- markdownlint-disable -->

<a href="../../../src/concrete/ml/pytest/utils.py#L0"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

# <kbd>module</kbd> `concrete.ml.pytest.utils`

Common functions or lists for test files, which can't be put in fixtures.

## **Global Variables**

- **MODELS_AND_DATASETS**
- **UNIQUE_MODELS_AND_DATASETS**

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L144"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `get_sklearn_linear_models_and_datasets`

```python
get_sklearn_linear_models_and_datasets(
    regressor: bool = True,
    classifier: bool = True,
    unique_models: bool = False,
    select: Optional[str, List[str]] = None,
    ignore: Optional[str, List[str]] = None
) → List
```

Get the pytest parameters to use for testing linear models.

**Args:**

- <b>`regressor`</b> (bool):  If regressors should be selected.
- <b>`classifier`</b> (bool):  If classifiers should be selected.
- <b>`unique_models`</b> (bool):  If each models should be represented only once.
- <b>`select`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) match the given string or list of strings. Default to None.
- <b>`ignore`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) do not match the given string or list of strings. Default to None.

**Returns:**

- <b>`List`</b>:  The pytest parameters to use for testing linear models.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L187"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `get_sklearn_tree_models_and_datasets`

```python
get_sklearn_tree_models_and_datasets(
    regressor: bool = True,
    classifier: bool = True,
    unique_models: bool = False,
    select: Optional[str, List[str]] = None,
    ignore: Optional[str, List[str]] = None
) → List
```

Get the pytest parameters to use for testing tree-based models.

**Args:**

- <b>`regressor`</b> (bool):  If regressors should be selected.
- <b>`classifier`</b> (bool):  If classifiers should be selected.
- <b>`unique_models`</b> (bool):  If each models should be represented only once.
- <b>`select`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) match the given string or list of strings. Default to None.
- <b>`ignore`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) do not match the given string or list of strings. Default to None.

**Returns:**

- <b>`List`</b>:  The pytest parameters to use for testing tree-based models.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L219"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `get_sklearn_neural_net_models_and_datasets`

```python
get_sklearn_neural_net_models_and_datasets(
    regressor: bool = True,
    classifier: bool = True,
    unique_models: bool = False,
    select: Optional[str, List[str]] = None,
    ignore: Optional[str, List[str]] = None
) → List
```

Get the pytest parameters to use for testing neural network models.

**Args:**

- <b>`regressor`</b> (bool):  If regressors should be selected.
- <b>`classifier`</b> (bool):  If classifiers should be selected.
- <b>`unique_models`</b> (bool):  If each models should be represented only once.
- <b>`select`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) match the given string or list of strings. Default to None.
- <b>`ignore`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) do not match the given string or list of strings. Default to None.

**Returns:**

- <b>`List`</b>:  The pytest parameters to use for testing neural network models.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L283"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `get_sklearn_neighbors_models_and_datasets`

```python
get_sklearn_neighbors_models_and_datasets(
    regressor: bool = True,
    classifier: bool = True,
    unique_models: bool = False,
    select: Optional[str, List[str]] = None,
    ignore: Optional[str, List[str]] = None
) → List
```

Get the pytest parameters to use for testing neighbor models.

**Args:**

- <b>`regressor`</b> (bool):  If regressors should be selected.
- <b>`classifier`</b> (bool):  If classifiers should be selected.
- <b>`unique_models`</b> (bool):  If each models should be represented only once.
- <b>`select`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) match the given string or list of strings. Default to None.
- <b>`ignore`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) do not match the given string or list of strings. Default to None.

**Returns:**

- <b>`List`</b>:  The pytest parameters to use for testing neighbor models.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L315"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `get_sklearn_all_models_and_datasets`

```python
get_sklearn_all_models_and_datasets(
    regressor: bool = True,
    classifier: bool = True,
    unique_models: bool = False,
    select: Optional[str, List[str]] = None,
    ignore: Optional[str, List[str]] = None
) → List
```

Get the pytest parameters to use for testing all models available in Concrete ML.

**Args:**

- <b>`regressor`</b> (bool):  If regressors should be selected.
- <b>`classifier`</b> (bool):  If classifiers should be selected.
- <b>`unique_models`</b> (bool):  If each models should be represented only once.
- <b>`select`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) match the given string or list of strings. Default to None.
- <b>`ignore`</b> (Optional\[Union\[str, List\[str\]\]\]):  If not None, only return models which names (or  a part of it) do not match the given string or list of strings. Default to None.

**Returns:**

- <b>`List`</b>:  The pytest parameters to use for testing all models available in Concrete ML.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L377"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `instantiate_model_generic`

```python
instantiate_model_generic(model_class, n_bits, **parameters)
```

Instantiate any Concrete ML model type.

**Args:**

- <b>`model_class`</b> (class):  The type of the model to instantiate.
- <b>`n_bits`</b> (int):  The number of quantization to use when initializing the model. For QNNs,  default parameters are used based on whether `n_bits` is greater or smaller than 8.
- <b>`parameters`</b> (dict):  Hyper-parameters for the model instantiation. For QNNs, these parameters  will override the matching default ones.

**Returns:**

- <b>`model_name`</b> (str):  The type of the model as a string.
- <b>`model`</b> (object):  The model instance.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L423"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `data_calibration_processing`

```python
data_calibration_processing(data, n_sample: int, targets=None)
```

Reduce size of the given data-set.

**Args:**

- <b>`data`</b>:  The input container to consider
- <b>`n_sample`</b> (int):  Number of samples to keep if the given data-set
- <b>`targets`</b>:  If `dataset` is a `torch.utils.data.Dataset`, it typically contains both the data  and the corresponding targets. In this case, `targets` must be set to `None`.  If `data` is instance of `torch.Tensor` or 'numpy.ndarray`, `targets\` is expected.

**Returns:**

- <b>`Tuple[numpy.ndarray, numpy.ndarray]`</b>:  The input data and the target (respectively x and y).

**Raises:**

- <b>`TypeError`</b>:  If the 'data-set' does not match any expected type.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L484"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `load_torch_model`

```python
load_torch_model(
    model_class: Module,
    state_dict_or_path: Optional[str, Path, Dict[str, Any]],
    params: Dict,
    device: str = 'cpu'
) → Module
```

Load an object saved with torch.save() from a file or dict.

**Args:**

- <b>`model_class`</b> (torch.nn.Module):  A PyTorch or Brevitas network.
- <b>`state_dict_or_path`</b> (Optional\[Union\[str, Path, Dict\[str, Any\]\]\]):  Path or state_dict
- <b>`params`</b> (Dict):  Model's parameters
- <b>`device`</b> (str):   Device type.

**Returns:**

- <b>`torch.nn.Module`</b>:  A PyTorch or Brevitas network.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L514"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `values_are_equal`

```python
values_are_equal(value_1: Any, value_2: Any) → bool
```

Indicate if two values are equal.

This method takes into account objects of type None, numpy.ndarray, numpy.floating, numpy.integer, numpy.random.RandomState or any instance that provides a `__eq__` method.

**Args:**

- <b>`value_2`</b> (Any):  The first value to consider.
- <b>`value_1`</b> (Any):  The second value to consider.

**Returns:**

- <b>`bool`</b>:  If the two values are equal.

______________________________________________________________________

<a href="../../../src/concrete/ml/pytest/utils.py#L558"><img align="right" style="float:right;" src="https://img.shields.io/badge/-source-cccccc?style=flat-square"></a>

## <kbd>function</kbd> `check_serialization`

```python
check_serialization(
    object_to_serialize: Any,
    expected_type: Type,
    equal_method: Optional[Callable] = None,
    check_str: bool = True
)
```

Check that the given object can properly be serialized.

This function serializes all objects using the `dump`, `dumps`, `load` and `loads` functions from Concrete ML. If the given object provides a `dump` and `dumps` method, they are also serialized using these.

**Args:**

- <b>`object_to_serialize`</b> (Any):  The object to serialize.
- <b>`expected_type`</b> (Type):  The object's expected type.
- <b>`equal_method`</b> (Optional\[Callable\]):  The function to use to compare the two loaded objects.  Default to `values_are_equal`.
- <b>`check_str`</b> (bool):  If the JSON strings should also be checked. Default to True.
