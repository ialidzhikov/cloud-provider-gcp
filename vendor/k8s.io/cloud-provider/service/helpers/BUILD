load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["helper.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/cloud-provider/service/helpers",
    importpath = "k8s.io/cloud-provider/service/helpers",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/core/v1:go_default_library",
        "//vendor/k8s.io/utils/net:go_default_library",
    ],
)
