add_subdirectory(cgltf)
add_subdirectory(cxxopts)
add_subdirectory(fmt)
add_subdirectory(glfw)
add_subdirectory(meshoptimizer)
add_subdirectory(robin_hood_hashing)

if(TUNDRA_ENABLE_VULKAN_SUPPORT)
    add_subdirectory(vk_mem_alloc)
    add_subdirectory(vulkan_headers)
endif(TUNDRA_ENABLE_VULKAN_SUPPORT)
