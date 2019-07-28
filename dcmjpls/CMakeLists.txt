# declare project
project(dcmjpls)

# recurse into subdirectories
foreach(SUBDIR libsrc apps include)
  add_subdirectory(${SUBDIR})
endforeach()
