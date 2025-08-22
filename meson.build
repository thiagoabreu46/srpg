project('main', 'c',
    default_options: 'default_library=static')

sdl2_dep = dependency('sdl2', 'gl', 'system')

executable('main', 'main.c',
    win_subsystem: 'windows',
    dependencies: [sdl2_dep])
