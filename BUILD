load("@rules_cc//cc:defs.bzl", "cc_library", "cc_import", "cc_binary", "cc_test")

cc_library(
    name = "rplidar_sdk",
    srcs = glob([
        "src/**/*.cpp",
    ]),
    hdrs = glob([
        "include/**/*.h",
        "src/**/*.h",
        "src/**/*.hpp",
    ]),
    copts = [
        "-Iinclude",
        "-Isrc",
    ],
    visibility = [
        "//visibility:public"
    ],
)
