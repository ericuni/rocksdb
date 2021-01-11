cc_library(
  name = 'status',
  hdrs = 'rocksdb/status.h',
  srcs = 'status.cc',
)

cc_library(
  name = 'slice',
  hdrs = 'rocksdb/slice.h',
  srcs = 'slice.cc',
  deps = [
    '//table:cleanable',
  ]
)

cc_test(
  name = 'slice_test',
  srcs = 'slice_test.cc',
  deps = [
    ':slice',
    '//port:stack_trace',
  ]
)

cc_library(
  name = 'coding',
  hdrs = 'coding.h',
  srcs = 'coding.cc',
)

cc_test(
  name = 'coding_test',
  srcs = 'coding_test.cc',
  deps = [
    ':coding',
    ':slice',
  ]
)
