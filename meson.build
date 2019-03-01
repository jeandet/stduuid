project('stduuid', 'cpp', version:'1.0.0', license:'MIT', default_options : ['warning_level=3', 'cpp_std=c++14'])

stduuid_inc = include_directories('include')
args = []
if target_machine.system()=='windows'
  args += '-D_SCL_SECURE_NO_WARNINGS'
endif


stduuid_dep = declare_dependency(
  include_directories : stduuid_inc,
  compile_args: args
)
