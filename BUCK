cxx_library(
  name = 'mpc',
  header_namespace = 'mpc',
  exported_headers = subdir_glob([
    ('.', '*.h'),
  ]),
  srcs = ['mpc.c'],
  visibility = ['PUBLIC']
)

cxx_test(
  name = 'test',
  deps = [':mpc'],
  srcs = glob([
    'tests/*.c',
  ]),
)
