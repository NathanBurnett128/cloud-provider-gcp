load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "jsonschema",
    srcs = [
        "base.go",
        "display.go",
        "models.go",
        "operations.go",
        "reader.go",
        "writer.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/gnostic/jsonschema",
    importpath = "github.com/google/gnostic/jsonschema",
    visibility = ["//visibility:public"],
    deps = ["//vendor/gopkg.in/yaml.v3:yaml_v3"],
)
