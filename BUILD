load("@bazel_gazelle//:def.bzl", "gazelle")
load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library", "go_test")

# gazelle:prefix github.com/davidsmd/etcd

gazelle(
    name = "gazelle",
    prefix = "github.com/davidsmd/etcd",
)

go_library(
    name = "go_default_library",
    srcs = ["main.go"],
    importpath = "github.com/davidsmd/etcd",
    visibility = ["//visibility:public"],
    deps = ["//etcdmain:go_default_library"],
)

go_binary(
    name = "etcd",
    embed = [":go_default_library"],
    visibility = ["//visibility:public"],
)

go_test(
    name = "go_default_test",
    srcs = ["main_test.go"],
    embed = [":go_default_library"],
)
