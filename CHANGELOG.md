
# Change Log

## 1.2.1 - 2017-09-13

- Better support for binary data in table uploads and parameters
- Add integer missing value support
- Allow list parameters to also be sets
- Improve connection protocol detection
- Add `eval` method to `CASTable`

## 1.2.0 - 2017-05-02

- Use `upload` action rather than `addtable` for `read_*` methods.
- Add basic Zeppelin notebook support (`from swat.notebook.zeppelin import show`)

## 1.1.0 - 2017-03-21

- Add support for Python 3.6 (Linux extension)
- Implement `sample` method on `CASTable`
- Add sampling support to plotting methods
- `cas.dataset.max_rows_fetched` increased to 10,000
- Add `terminate` method to `CAS` object to end session and close connection
- Implement `fillna`, `replace`, and `dropna` methods on `CASTable`
- Add `apply_labels` method on `SASDataFrame` to set column labels as column names

## 1.0.0 - 2016-09-27

- Initial Release
