Data files for Crustal Thickness Compilation for South America :

Compilation_Marcelo*   754  data points
Compilation_Andres*    183  data points

cat Compilation_Marcelo.06NOV2012.IXYEHU.dat Compilation_Andres.XYEHU.dat \
 | awk '(NF>4)' > Compilation_SAm.06NOV2012.IXYEHU.dat

Compilation_SAm.06NOV2012.IXYEHU.dat = compilation of all 937 points
  Moho thickness for South America (Assumpcao et al., 2013a,b).
 (there are a few repeated stations…)
  columns are:
I = Identification (usually station name)
X,Y = long., lat.
E = elevation above msl
H = crustal THICKNESS !!!
    includes topography in continents
    includes ocean layer in oceanic part!
U = uncertainty

other columns are references/observations


model 1:  Seismic constraints (added some gravity-derived controls)

model 3:  Seismic constraints + gravity derived controls + surface-wave tomography


