load("//tools:cpplint.bzl", "cpplint")

package(default_visibility = ["//visibility:public"])

cc_proto_library(
    name = "lgsvl_proto",
    deps = [
        ":lgsvl_lib",
    ],
)

proto_library(
    name = "lgsvl_lib",
    srcs = [
        "detection2d.proto",
        "detection2darray.proto",
        "detection3d.proto",
        "detection3darray.proto",
    ],
    deps = [
	"//modules/common/proto:header_proto_lib",
	"//modules/common/proto:error_code_proto_lib",
        "//modules/common/proto:geometry_proto_lib",
    ],
)

