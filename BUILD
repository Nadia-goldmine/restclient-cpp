cc_library(
    name = "restclient",
    srcs = glob(["**/source/*.cc"]),
    hdrs = glob(["**/restclient-cpp/*.h"]),
    includes = ["./include"],
    visibility = ["//visibility:public"],
    deps = [
        "@curl//:curl"
    ]
)
