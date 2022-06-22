project('Learning C++', version: '1.0', meson_version: '>=0.62.0')

hotdoc = import('hotdoc')

hotdoc.generate_doc(meson.project_name(),
    project_version: meson.project_version(),
    sitemap: 'sitemap.txt',
    index: 'notebook/index.md',
    include_paths: ['notebook'],
    build_by_default: true,
    syntax_highlighting_activate: true,
    keep_markup_in_code_blocks: true,
    install: false)
