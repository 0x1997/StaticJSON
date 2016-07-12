project('StaticJSON', 'cpp')

inc = include_directories('include')

install_headers(
    'staticjson/basic.hpp',
    'staticjson/error.hpp',
    'staticjson/io.hpp',
    'staticjson/primitive_types.hpp',
    'staticjson/staticjson.hpp',
    'staticjson/stl_types.hpp',
    subdir: 'staticjson'
)

lib = object_library('StaticJSON',
    'src/staticjson.cpp',
    cpp_args: ['-fPIC']
)
