client_src = files([
    'client.c',
])

client_exe = executable('client', client_src,
    dependencies: open62541_dep,
)

server_src = files([
    'server.c',
])

server_exe = executable('server', server_src,
    dependencies: open62541_dep,
)
