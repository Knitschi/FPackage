include(cpfPackageProject)
include(cpfAddCppPackageComponent)

set( PACKAGE_PUBLIC_HEADER
	function.h
)

set( PACKAGE_PRODUCTION_FILES
	function.cpp
)

############################################## Add Package #################################
cpfAddCppPackageComponent( 
	TYPE					LIB
	PUBLIC_HEADER			${PACKAGE_PUBLIC_HEADER}
	PRODUCTION_FILES		${PACKAGE_PRODUCTION_FILES}
	ENABLE_PACKAGE_DOX_FILE_GENERATION TRUE
)
