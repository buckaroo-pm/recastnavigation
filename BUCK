load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'recast',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('Recast/Include', '**/*.h'),
  ]),
  srcs = glob([
    'Recast/Source/**/*.cpp',
  ]),
  visibility = [
    'PUBLIC',
  ],
)
