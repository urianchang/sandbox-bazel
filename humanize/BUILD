load("@io_bazel_rules_go//go:def.bzl", "go_binary")

go_binary(
    name = "api",
    srcs = ["main.go"],
    out = "humanize",
    deps = [
        "//humanize/pkg/duration",
        "@com_github_gin_gonic_gin//:go_default_library",
    ],
)
