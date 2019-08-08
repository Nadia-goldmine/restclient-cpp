cc_library(
    name = "restclient",
    copts = ["-std=c++0x"],
    srcs = glob(["**/source/*.cc"]),
    hdrs = glob(["**/restclient-cpp/*.h"]),
    includes = ["./include"],
    visibility = ["//visibility:public"],
    deps = [
        "@curl//:curl"
    ]
)
