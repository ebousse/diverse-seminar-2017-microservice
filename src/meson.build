diverse_seminar_2017_microservice_sources = [
  'main.vala'
]

diverse_seminar_2017_microservice_deps = [
  dependency('gio-2.0', version: '>= 2.50'),
  dependency('glib-2.0'),
  dependency('gobject-2.0'),
  dependency('libsoup-2.4'),
  subproject('valum').get_variable('vsgi'),
  subproject('valum').get_variable('valum')
]


executable('diverse-seminar-2017-microservice', diverse_seminar_2017_microservice_sources,
  vala_args: '--target-glib=2.50',
  dependencies: diverse_seminar_2017_microservice_deps,
  install: true,
)
