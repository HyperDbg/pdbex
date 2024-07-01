set(SourceFiles
    "HyperDbgIntegration.cpp"
    "main.cpp"
    "PDB.cpp"
    "PDBExtractor.cpp"
    "PDBHeaderReconstructor.cpp"
    "HyperDbgExport.h"
    "HyperDbgGlobals.h"
    "PDB.h"
    "PDBCallback.h"
    "PDBExtractor.h"
    "PDBHeaderReconstructor.h"
    "PDBReconstructorBase.h"
    "PDBSymbolSorterAlphabetical.h"
    "PDBSymbolSorterBase.h"
    "PDBSymbolVisitorBase.h"
    "PDBSymbolVisitor.h"
    "PDBSymbolSorter.h"
    "UdtFieldDefinition.h"
    "UdtFieldDefinitionBase.h"
)
include_directories( "DIA SDK/include" )
add_library(pdbex SHARED ${SourceFiles})
