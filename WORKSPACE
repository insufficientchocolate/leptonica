workspace(name = "leptonica")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

http_archive(
    name = "webp",
    build_file = "//third_party:BUILD.webp",
    sha256 = "b4baa22501accc12e59bdf872b41b906e52f8522d3fe11a566bd654f3975b3f1",
    strip_prefix = "libwebp-1.0.2",
    urls = ["https://github.com/webmproject/libwebp/archive/v1.0.2.zip"],
)

# mozjpeg bazel WIP
git_repository(
    name = "mozjpeg",
    branch = "bazel",
    remote = "https://github.com/tony84727/mozjpeg",
)
