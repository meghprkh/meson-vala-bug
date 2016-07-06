project('valaprog', ['c', 'vala'])

glib = dependency('glib-2.0')
gobject = dependency('gobject-2.0')

executable('valaprog', ['main.vala', 'test.vala', 'subdir/test.vala'],
           dependencies : [glib, gobject])
