open62541_src = files([
    'open62541.c',
])

open62541_inc = include_directories('.')

open62541_lib = library('open62541', open62541_src,
    include_directories: open62541_inc,
)

open62541_dep = declare_dependency(
    link_with: open62541_lib,
    include_directories: open62541_inc,
)
