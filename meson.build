project('Yaru-Fedora',
        version: '20.04',
        meson_version: '>= 0.45',
        license : ['GPL3', 'CC BY-SA 4.0'],
        default_options: ['prefix=/usr'])

components = ['icons', 'gnome-shell', 'gtk']

foreach component: components
  if get_option(component)
    subdir(component)
  endif
endforeach
