new_local_repository(
    name = "opencv",
    path = "/usr/local/Cellar/opencv/3.4.5",
    build_file = "opencv.BUILD",
)

new_local_repository(
  name = "boost",
  path = "/usr/local/Cellar/boost/1.68.0",
  build_file = "boost.BUILD",
)

new_http_archive(
    name = "gtest",
    url = "https://github.com/google/googletest/archive/release-1.7.0.zip",
    sha256 = "b58cb7547a28b2c718d1e38aee18a3659c9e3ff52440297e965f5edffe34b6d0",
    build_file = "gtest.BUILD",
    strip_prefix = "gtest-1.7.0",
)
