package(default_visibility = ["//visibility:public"])
licenses(["notice"]) # MIT license

cc_library(
  name = "gflags-20",
  includes = ["src"],
  hdrs = glob(["src/gflags/*.h"]),
  copts = [
    "-O",
    "-Wall",
    "-Wwrite-strings",
    "-Woverloaded-virtual",
    "-Wno-sign-compare",
    "-Wno-unused-local-typedefs",
    "-DNDEBUG",
    "-pthread",
  ],
  linkopts = [
    #"-pthread",
  ],
  linkstatic = 1,
  srcs = [
    "src/gflags/gflags.h",
    "src/gflags/gflags_completions.h",
    "src/gflags/gflags_declare.h",
    "src/google/gflags.h",
    "src/google/gflags_completions.h",
    "src/config.h",
    "src/gflags.cc",
    "src/gflags_completions.cc",
    "src/gflags_nc.cc",
    "src/gflags_reporting.cc",
    "src/mutex.h",
    "src/util.h",
  ],
  deps = [],
)
