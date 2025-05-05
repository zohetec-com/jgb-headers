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
       	DESTINATION include/jgb)
