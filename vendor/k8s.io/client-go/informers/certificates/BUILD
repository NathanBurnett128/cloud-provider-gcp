load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "certificates",
    srcs = ["interface.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/informers/certificates",
    importpath = "k8s.io/client-go/informers/certificates",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/client-go/informers/certificates/v1:certificates",
        "//vendor/k8s.io/client-go/informers/certificates/v1beta1",
        "//vendor/k8s.io/client-go/informers/internalinterfaces",
    ],
)
