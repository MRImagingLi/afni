project(PYTHON_SCRIPTS)
file(GLOB PYTHON_SCRIPTS "afni_python/*.py")

install(
  PROGRAMS ${PYTHON_SCRIPTS}
  DESTINATION ${AFNI_INSTALL_RUNTIME_DIR}
  COMPONENT Runtime
)