load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "traits",
    srcs = [
        "comparer.go",
        "container.go",
        "field_tester.go",
        "indexer.go",
        "iterator.go",
        "lister.go",
        "mapper.go",
        "matcher.go",
        "math.go",
        "receiver.go",
        "sizer.go",
        "traits.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/cel-go/common/types/traits",
    importpath = "github.com/google/cel-go/common/types/traits",
    visibility = ["//visibility:public"],
    deps = ["//vendor/github.com/google/cel-go/common/types/ref"],
)
