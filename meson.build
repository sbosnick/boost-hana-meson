# Copyright 2016 Steven Bosnick
# This file is released under the terms of the Boost Software
# License version 1.0. See the file COPYING for your 
# rights under that license.

project('boost-hana', 'cpp', version:'0.6.0', license:'boost')

if not meson.is_subproject()
    error('The meson support for boost hana is designed for hana as a subproject')
endif

hana = declare_dependency(include_directories: 'include')
