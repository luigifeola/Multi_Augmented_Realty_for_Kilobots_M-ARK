# If Qt+OpenGL dependencies were found, descend into these directories
if(ARGOS_COMPILE_QTOPENGL)
	add_subdirectory(kilobot_ALF_dhtf)
	add_subdirectory(CRE_ALF)
endif(ARGOS_COMPILE_QTOPENGL)
