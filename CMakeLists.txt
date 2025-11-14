cmake_minimum_required(VERSION 3.5)

project(
    jgb-headers
    VERSION 0.1
)

install(FILES
       	include/config_factory.h
      	include/config.h
      	include/schema.h
      	include/log.h
      	include/error.h
      	include/helper.h
       	include/app.h
       	include/core.h
       	include/buffer.h
       	misc/check_u32_context.h
       	misc/write_32u_context.h
       	DESTINATION include/jgb)
