add_executable(logging_application
  logging.cpp
)
target_link_libraries(logging_application stuff)
set_target_properties(logging_application PROPERTIES OUTPUT_NAME logging_example)
