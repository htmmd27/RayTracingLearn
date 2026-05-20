cmake_minimum_required(VERSION 3.28)
project(RayTracingInOneWeek)

set(CMAKE_CXX_STANDARD 17)

add_executable(RayTracingInOneWeek main.cpp
        Utilities/vec3.h
        Utilities/color.h
        Utilities/ray.h
        Hittable/hittable.h
        Hittable/sphere.h
        Hittable/hittable_list.h
        Common/rtweekend.h
        Utilities/interval.h
        Common/camera.h
        Common/material.h
        Utilities/aabb.h
        Hittable/bvh.h
        Common/texture.h
        External/stb_image.h
        Common/rtw_stb_image.h
        Utilities/perlin.h
)
