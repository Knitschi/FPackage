include(cpfAddCppPackageComponent)

set( PACKAGE_PUBLIC_HEADER
	function.h
)

############################################## Add Package #################################
cpfAddCppPackageComponent( 
	TYPE					INTERFACE_LIB
	PUBLIC_HEADER			${PACKAGE_PUBLIC_HEADER}
	ENABLE_PACKAGE_DOX_FILE_GENERATION TRUE
)
