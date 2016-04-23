add_library(cbench cbench.c)
if (UNIX)
  target_link_libraries(cbench m)
endif(UNIX)
