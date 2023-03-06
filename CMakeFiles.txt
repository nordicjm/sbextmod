# Add test module
set(tmp ${SYSBUILD_EXTRA_TOOLS})
list(APPEND tmp ${CMAKE_CURRENT_LIST_DIR}/test_mod)
set(SYSBUILD_EXTRA_TOOLS ${tmp} PARENT_SCOPE)
