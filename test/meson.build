i2c_proj = subproject('i2c')
i2c_dep = i2c_proj.get_variable('i2c_dep')

exe = executable('test_i2c', files('test_i2c.c'),
  dependencies: i2c_dep,
  c_args: cflags,
)

test(exe.name(), exe)