# GO STUFF

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_go",
    urls = ["https://github.com/bazelbuild/rules_go/releases/download/0.13.0/rules_go-0.13.0.tar.gz"],
    sha256 = "ba79c532ac400cefd1859cbc8a9829346aa69e3b99482cd5a54432092cbc3933",
)

http_archive(
    name = "bazel_gazelle",
    urls = ["https://github.com/bazelbuild/bazel-gazelle/releases/download/0.13.0/bazel-gazelle-0.13.0.tar.gz"],
    sha256 = "bc653d3e058964a5a26dcad02b6c72d7d63e6bb88d94704990b908a1445b8758",
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")

go_rules_dependencies()

go_register_toolchains()

load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies", "go_repository")

gazelle_dependencies()





go_repository(
    name = "com_github_dgrijalva_jwt",
    commit = "a539ee1a749a2b895533f979515ac7e6e0f5b650",
    importpath = "github.com/dgrijalva/jwt-go",
)

go_repository(
    name = "com_github_coreos_go_semver",
    commit = "1817cd4bea52af76542157eeabd74b057d1a199e",
    importpath = "github.com/coreos/go-semver",
)

go_repository(
    name = "com_github_coreos_pkg",
    commit = "8dbaa491b063ed47e2474b5363de0c0db91cf9f2",
    importpath = "github.com/coreos/pkg",
)

go_repository(
    name = "com_github_jonboulle_clockwork",
    commit = "bcac9884e7502bb2b474c0339d889cb981a2f27f",
    importpath = "github.com/jonboulle/clockwork",
)

go_repository(
    name = "com_github_coreos_go_systemd",
    commit = "d2196463941895ee908e13531a23a39feb9e1243",
    importpath = "github.com/coreos/go-systemd",
)

go_repository(
    name = "com_github_coreos_bbolt",
    commit = "48ea1b39c25fc1bab3506fbc712ecbaa842c4d2d",
    importpath = "github.com/coreos/bbolt",
)

go_repository(
    name = "com_github_spf13_pflag",
    commit = "3ebe029320b2676d667ae88da602a5f854788a8a",
    importpath = "github.com/spf13/pflag",
)


go_repository(
    name = "com_github_spf13_cobra",
    commit = "a114f312e075f65bf30d6d9a1430113f857e543b",
    importpath = "github.com/spf13/cobra",
)

go_repository(
    name = "com_github_google_btree",
    commit = "e89373fe6b4a7413d7acd6da1725b83ef713e6e4",
    importpath = "github.com/google/btree",
)

go_repository(
    name = "com_github_ugorji_gocodec",
    commit = "9b066cfc2ed2d647967a46613f93474656a89300",
    importpath = "github.com/ugorji/go",
)


go_repository(
    name = "com_github_soheilhy_cmux",
    commit = "f7603f4e1c90a14f48a7170db2d625c5ce04db6b",
    importpath = "github.com/soheilhy/cmux",
)

go_repository(
    name = "com_github_ghodss_yaml",
    commit = "e9ed3c6dfb39bb1a32197cb10d527906fe4da4b6",
    importpath = "github.com/ghodss/yaml",
)


go_repository(
    name = "com_github_grpc_ecosystem_go_grpc_prometheus",
    commit = "c225b8c3b01faf2899099b768856a9e916e5087b",
    importpath = "github.com/grpc-ecosystem/go-grpc-prometheus",
)


go_repository(
    name = "com_github_prometheus_client_golang",
    commit = "c5b7fccd204277076155f10851dad72b76a49317",
    importpath = "github.com/prometheus/client_golang",
)