go_library(
    name = "tar",
    srcs = ["tar.go"],
    visibility = ["//tools/jarcat/..."],
    deps = ["//third_party/go:xz"],
)

go_test(
    name = "tar_test",
    srcs = ["tar_test.go"],
    data = ["test_data"],
    deps = [
        ":tar",
        "//third_party/go:testify",
        "//third_party/go:xz",
    ],
)
