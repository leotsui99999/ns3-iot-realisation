
set(name object-names)
set(source_files ${name}.cc)
set(header_files)
set(libraries_to_link ${libcore} ${libcsma} ${libinternet} ${libapplications})
build_example ("${name}" "${source_files}" "${header_files}" "${libraries_to_link}")


