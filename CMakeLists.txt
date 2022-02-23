include(cpfPackageProject)

cpfPackageProject(
    BRIEF_DESCRIPTION "A dummy package with two components that is used to test the CMakeProjectFramework."
    LONG_DESCRIPTION ""
    OWNER Knitschi
    WEBPAGE_URL "https://github.com/Knitschi/FPackage"
    TARGET_NAMESPACE f
    COMPONENTS
        Component1
        Component2
    PACKAGE_FILES
        LICENSE
        README.md
	PACKAGE_ARCHIVES
		PACKAGE_ARCHIVE_CONTENT_TYPE 	CT_DEVELOPER
		PACKAGE_ARCHIVE_FORMATS 		7Z
)
