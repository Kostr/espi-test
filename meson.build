project(
    'oob-pch-test',
    'cpp',
    default_options: [
        'warning_level=3',
        'cpp_std=c++23'
    ],
    license: 'Apache-2.0',
    version: '0.1',
    meson_version: '>=1.1.1',
)

add_project_arguments(
    '-Wno-psabi',
    language: 'cpp',
)

executable(
  'oob-pch-test',
  'oob-pch-test.cpp',
  include_directories: include_directories('.'),
  install: true,
  install_dir: get_option('bindir'))

executable(
  'mafs-test',
  'mafs-test.cpp',
  include_directories: include_directories('.'),
  install: true,
  install_dir: get_option('bindir'))
