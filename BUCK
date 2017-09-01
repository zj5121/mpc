cxx_library(
  name = 'mpc',
  licenses = ['LICENSE.md'],
  header_namespace = 'mpc',
  exported_headers = ['mpc.h'],
  headers = ['mpc.h'],
  srcs = ['mpc.c'],
  visibility = ['PUBLIC'],
)

cxx_test(
  name = 'test',
  deps = [':mpc'],
  srcs = glob([
    'tests/*.c',
  ]),
)
