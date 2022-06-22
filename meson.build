project('Learning Module', version: 1.0, meson_version: '>=0.62.0')

hotdoc = import('hotdoc')

hotdoc.generate_doc(meson.project_name(),
    project_version: meson.project_version(),
    sitemap: 'sitemap.txt',
    index: 'notebook/index.md',
    languages: ['c'],
    install: true)
