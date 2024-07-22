# DCW-type-files
This repository contains optional netCDF files to use instead of the Digital Chart of the World [DCW](https://github.com/GenericMappingTools/dcw-gmt)
The best way to make use these files is to place them in the same directory as the default `dcw-gmt.nc`, which is normally located at .../share/dcw.
Then, on a GMT version > 6.5.0, we use it via the **+f** modifier of the **-E** `coast` option. For example, **-E**IT+fODS will use the Italy polygons
contained in the _ODS.nc_ file (data from [opendatasoft](https://public.opendatasoft.com/explore/dataset/world-administrative-boundaries)). However,
user may select to put these files eleswhere but then the **-f** modifier usage must include data's full file name (whitout the `.nc` extension).

Currently we have available the [ODS](https://public.opendatasoft.com/explore/dataset/world-administrative-boundaries), NE10m and NE110m from
[Natural Earth](https://www.naturalearthdata.com/)
that can be downloaded from [GitHub releases](https://github.com/GenericMappingTools/DCW-type_files/releases)
