load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "strategicpatch",
    srcs = [
        "errors.go",
        "meta.go",
        "patch.go",
        "types.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apimachinery/pkg/util/strategicpatch",
    importpath = "k8s.io/apimachinery/pkg/util/strategicpatch",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured",
        "//vendor/k8s.io/apimachinery/pkg/util/json",
        "//vendor/k8s.io/apimachinery/pkg/util/mergepatch",
        "//vendor/k8s.io/apimachinery/third_party/forked/golang/json",
        "//vendor/k8s.io/kube-openapi/pkg/util/proto",
    ],
)
