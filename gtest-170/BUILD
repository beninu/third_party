package(default_visibility = ["//visibility:public"])
licenses(["notice"]) # MIT license

cc_library(
  name = "gtest-170",
  includes = ["include"],
  hdrs = glob(["include/gtest/*.h"]),
  copts = [
    "-DGTEST_HAS_PTHREAD=1",
    "-g",
    "-O2",
    "-Wall",
    "-Wextra",
    "-Wno-missing-field-initializers",
    "-pthread",
    "-I./third_party/gtest-170",
  ],
  linkopts = ["-pthread"],
  linkstatic = 1,
  srcs = glob(
    [
    "src/*.cc",
    "src/*.h",
    "include/gtest/*.h",
    "include/gtest/internal/*.h",
    ],
    exclude = ["src/gtest-all.cc"],
  ),
  deps = [],
)
