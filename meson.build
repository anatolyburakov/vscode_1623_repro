# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2019 Anatoly Burakov

project('VSCode Bug 1623', 'CPP',
	license: 'BSD',
	default_options: ['buildtype=release']
)

# treat all warnings as errors
add_global_arguments('-Wall', language : 'cpp')
add_global_arguments('-Werror', language : 'cpp')

files = [
    'error.cpp'
]

executable('vscode_1623', files)
