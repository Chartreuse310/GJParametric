# 将 src 下的所有 cpp 作为 main 的依赖
file(GLOB_RECURSE SRC_FILES
    "*.cpp"
)

add_executable(GJParametric ${SRC_FILES})

# OCCT 链接
target_link_libraries(GJParametric PRIVATE ${OpenCASCADE_LIBRARIES})
