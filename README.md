# HoudiniAlembicTree
A custom alembic import node used to replace alembic archive.

# Goals
Provides an option to limit the depth for generated nodes' hierarchy.

Includes a handy and efficient way to set materials without unpack Alembic Delayed Load Primitives.

Have a stornger camera import system that allows you to import animated focal length and so on.

Can automatically change the frame range of the playbar by reading the scale of the alembic file.

# Usage
Similar as the default Alembic Archive, input the filename, objectpath and other Alembic Loading Parameters and push the Build buttom, set the materials, remap attributes and the display option then push the Push buttom to sent these to kids.
