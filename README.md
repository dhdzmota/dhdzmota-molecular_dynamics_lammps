{\rtf1\ansi\ansicpg1252\deff0\nouicompat\deflang1033{\fonttbl{\f0\fnil\fcharset0 Calibri;}}
{\*\generator Riched20 10.0.18362}\viewkind4\uc1 
\pard\sa200\sl276\slmult1\f0\fs22\lang10 # Din\'e1mica Molecular con LAMMPS\par
Este repositorio contiene informaci\'f3n pertinente a la din\'e1mica molecular generada mediante LAMMPS para determinar si existe un proceso de nucleaci\'f3n de las mol\'e9culas de Fe(OH)$_3$ en medio acuoso, variando la concentraci\'f3n y la temperatura.\par
## Contenidos:\par
El contenido est\'e1 dividido en cuatro carpetas distintas:\par
- **Data_Analysis_python** contiene programas de python en formato de jupyter notebook para analizar los archivos obtenidos despu\'e9s de crear la din\'e1mica molecular. Estos archivos son tipo dump, .txt o .dat, que corresponden a las posiciones de las part\'edculas a traves de los pasos temporales, la determinaci\'f3n de la energ\'eda y a las funciones de distribuci\'f3n radial, respectivamente. \par
- **LAMMPS_files** contiene todas las dependencias necesarias para poder llevar a cabo la din\'e1mica molecular a travez de la consola (windows o ubuntu) mediante el comando __lmp/_mpi -in \{filename\} > \{outputname.txt\}__\par
- **Temp_variations** contiene los resultados de la din\'e1mica molecular en carpetas cuyo nombre es a la temperatura que fueron tomadas. Estas carpetas de temperatura tienen los archivos "dump.", ".dat" y ".txt" con los resultados de las simulaciones. Tambi\'e9n tienen otra carpeta images, donde se puede encontrar imagenes con el objetivo de hacer un archivo ".giff".   \par
- **Other files** contiene un archivo ".cml" para el software the Avogadro. Tiene un readme con informaci\'f3n referente al potencial y algunas referencias.\par
\par
}
 