# -*- python -*-
# This file contains rules for Bazel; see drake/doc/bazel.rst.

package(default_visibility = ["//visibility:public"])

# If you delete this rule, //subdir:subprogram will no longer be valid,
# because this rule is implicitly exporting foo.txt. 
cc_binary(
  name = "main",
  srcs = ["main.cc"],
  data = ["data/foo.txt"]
)

