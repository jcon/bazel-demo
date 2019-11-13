package(default_visibility = ["//visibility:public"])

load("@npm_bazel_typescript//:defs.bzl", "ts_devserver", "ts_library")

ts_library(
    name = "interpreter",
    module_name = "@lang/interpreter",
    srcs = glob(["*.ts"]),
    deps = ["//packages/lexer", "//packages/parser"],
)

