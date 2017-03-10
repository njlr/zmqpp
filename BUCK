include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'zmqpp',
  header_namespace = 'zmqpp',
  exported_headers = subdir_glob([
    ('src/zmqpp', '*.hpp'),
  ]),
  srcs = glob([
    'src/zmqpp/*.cpp',
  ]),
  compiler_flags = [
    '-std=c++14',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
