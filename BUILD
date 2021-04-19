load("@rules_cc//cc:defs.bzl", "cc_library", "cc_import", "cc_binary", "cc_test")

cc_library(
    name = "rplidar_sdk",
    srcs = glob(["src/*.cpp", "src/arch/linux/*.cpp", "src/hal/*.cpp"]),
    hdrs = glob(["include/*.h", "src/*.h", "src/arch/linux/*.h", "src/arch/linux/*.hpp", "src/hal/*.h"]),
    copts= ["-Iinclude/ -Isrc/"],
    visibility = ["//visibility:public"],
    linkstatic = 1,
)

