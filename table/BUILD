cc_library(
  name = 'cleanable',
  hdrs = 'rocksdb/cleanable.h',
  srcs = 'iterator.cc',
  deps = [
    '//util:status',
  ]
)

cc_test(
  name = 'cleanable_test',
  srcs = 'cleanable_test.cc',
  deps = [
    ':cleanable',
    '//port:stack_trace',
    '#glog',
  ]
)
