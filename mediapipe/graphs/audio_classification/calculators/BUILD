# Copyright 2019 The MediaPipe Authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

licenses(["notice"])

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "tflite_task_audio_classifier_calculator",
    srcs = ["tflite_task_audio_classifier_calculator.cc"],
    visibility = ["//visibility:public"],
    deps = [
        "@com_google_absl//absl/status",
        "@com_google_absl//absl/strings:str_format",
        "//mediapipe/framework:calculator_framework",
        "@org_tensorflow_lite_support//tensorflow_lite_support/examples/task/audio/desktop:audio_classifier_lib",
        "@org_tensorflow_lite_support//tensorflow_lite_support/cc/task/audio:audio_classifier",
    ],
    alwayslink = 1,
)
