cxx_library(
  name = 'imgui',
  header_namespace = '',
  exported_headers = [
    'imconfig.h',
    'imgui.h',
  ],
  headers = [
    'imgui_internal.h',
    'stb_rect_pack.h',
    'stb_textedit.h',
    'stb_truetype.h',
  ],
  srcs = [
    'imgui.cpp',
    'imgui_draw.cpp',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'demo',
  srcs = [
    'imgui_demo.cpp',
  ],
  deps = [
    ':imgui',
  ],
)
