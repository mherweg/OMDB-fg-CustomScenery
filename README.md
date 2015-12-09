# OMDB-fg-CustomScenery
Dubai Scenery for Flightgear with OMDB and OMDW

OMDB airport layout by gateway artist Litjan
terrain with osm coastline by d-laser

## optional: 

* non-textured buildings made with osm2city
* object locations for project3000 shared objects - you will need the project3000/Models/lib folder from here:
http://media.lug-marl.de/flightgear/project3000-Nov2015.tgz
or from here:    
https://github.com/mherweg/d-laser-fgtools/tree/master/Models/lib


## how to use:

fgfs --fg-scenery=/scenery/OMDB-fg-CustomScenery

optional:

fgfs--fg-scenery=/scenery/OMDB-fg-CustomScenery/project3000  
--fg-scenery=/mh/scenery/OMDB-fg-CustomScenery/osm2city    
--fg-scenery=/mh/scenery/OMDB-fg-CustomScenery



hint:

* link or copy your Terrasync Objects folder into the OMDB-fg-CustomScenery folder:

ln -s ~/.fgfs/TerraSync/Objects /scenery/OMDB-fg-CustomScenery


* remove the white Burj Khalifa (because we have it in TerraSync):

cd /scenery/OMDB-fg-CustomScenery/osm2city
rm e050n20_e055n25_3857609city0507.ac  e050n20_e055n25_3857609city0407.ac


