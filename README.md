---
dataset_info:
  features:
  - name: url
    dtype: string
  - name: archive
    dtype: string
  - name: title
    dtype: string
  - name: date
    dtype: timestamp[ns]
  - name: text
    dtype: string
  - name: summary
    dtype: string
  - name: compression
    dtype: float64
  - name: coverage
    dtype: float64
  - name: density
    dtype: float64
  - name: compression_bin
    dtype: string
  - name: coverage_bin
    dtype: string
  - name: density_bin
    dtype: string
  - name: __index_level_0__
    dtype: int64
  splits:
  - name: train
    num_bytes: 494667
    num_examples: 100
  - name: test
    num_bytes: 426888
    num_examples: 100
  - name: dev
    num_bytes: 358040
    num_examples: 100
  download_size: 884981
  dataset_size: 1279595
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: test
    path: data/test-*
  - split: dev
    path: data/dev-*
---
