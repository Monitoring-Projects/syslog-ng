add_unit_test(CRITERION TARGET test_loggen_filereader DEPENDS loggen_helper)
target_include_directories(test_loggen_filereader PUBLIC
  ${PROJECT_SOURCE_DIR}
  )
