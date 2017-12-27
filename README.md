# worldsim
WorldSim is my personal project. I want to develop a cloud based GIS that supports IoT. This means we are going to virtualize everything that in the world. Imagine using Google Earth as a first-person simulator and seeing people walking and cars moving around in real-time.

Every robot can connect to the Internet and load a virtual model of WorldSim on itself. This will allow it to use its sensors to contribute its local information to the cloud system, as well as access and use data of unknown environments, from other robots, from the cloud. Thus, a global environment modelling tool can be deployed for use in Robotics. 

P.S: This can also enable humans to experience the world in AR or VR. (Example: HBO: Westworld simulations)

**Simulation**: Earth and layers, to account for depth (underground). estimate of core to surface to atmosphere. voxel mapping according to imperial units. eventually we can use earth as reference point when mapping voxels in universe.

*we might need a linear time scale, as well as a new unit of 4-dim vector, to store 3-d values plus time at which state was recorded.*

**Surface: GIS Roadmap:**
 - Topography Data: Land/Sea + Height Map
 - Boundaries: Continents, Countries...see below
 - Street Data: Roads and Addreses.
 - Transportation: Populate roads with traffic
 - Buildings Data: (Occupied Land)
 - Vegetation Data: Trees, plants, etc.
 
 Goal: To create a simulation of the world, which can be acccess by physical robots for SLAM, as well as for virtual experiences by humans.


Level of Layers:
![Visual](https://upload.wikimedia.org/wikipedia/commons/7/73/Visual_Representation_of_Themes_in_a_GIS.jpg)

Can we eventually model every voxel in the universe ?
This knowledge base will be complemetary to my ROSCOG project (brain for a robot).


**Planet > Continents > Countries > States    > City/Town    > District > Road/Street Address > Co-ordinates (x,y,z)**
Earth  > America     > USA      > Virginia  > Alexandria   > Rosemont > 2823 King Street    > latitude, longitude and elevation

** Fields of Knowledge/Information/Data:**
Geodesy (geodetics engineering), Computer Sciences, Information Technology
