load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "Stencil",
    srcs = glob(["Sources/**/*.swift"]),
    visibility = ["//visibility:public"],
    deps = ["@PathKit"],
)
