load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "xxhash",
    srcs = [
        "xxhash.go",
        "xxhash_amd64.go",
        "xxhash_amd64.s",
        "xxhash_other.go",
        "xxhash_unsafe.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/cespare/xxhash/v2",
    importpath = "github.com/cespare/xxhash/v2",
    visibility = ["//visibility:public"],
)
