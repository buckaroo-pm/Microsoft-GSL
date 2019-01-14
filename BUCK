load('//:subdir_glob.bzl', 'subdir_glob')

prebuilt_cxx_library(
  name = 'gsl',
  header_only = True,
  header_namespace = 'gsl',
  exported_headers = subdir_glob([
    ('include/gsl', '**/*'),
  ]),
  licenses = [
    'LICENSE',
  ],
  visibility = [
    'PUBLIC',
  ],
)
