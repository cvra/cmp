cc_library(
    name = "cmp",
    srcs = [
        "cmp.c",
        "cmp.h",
    ],
    hdrs = ["cmp.h"],
    include_prefix = "cmp",
    visibility = ["//visibility:public"],
)

cc_test(
    name = "cmp-test",
    size = "small",
    srcs = glob([
        "test/*.c",
        "test/*.h",
    ]),
    deps = [":cmp"],
)
