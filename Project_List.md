# Notable Projects

## Digital Metabolic Twin Center, University of Galway

- OptArrow optimization engine
  - A group of microservices that allows using different solvers(GLPK, HiGHS, Gurobi, etc.) and their implementation in Python(through Pyomo) and Julia(Through JuMP) to solve mathematical optimization problems
  - Can solve LP(Linear Programming) and QP(Quadratic Programming) problems
  - Gateway service implemented using FastAPI
  - Dedicated service for each language (Pyomo and JuMP)
  - Connection to JuMP service via socket, and Pyomo service via gRPC
  - Uses Apache Arrow as a unified data exchange format to utilize their high performance capabilities

## Shenzhen Zhongdi Software Engineering Co,.Ltd

- MapGIS Board
  - A low-code platform that can be used to create single-page web systems with rich map and spatial data visualization functionalities
  - Used internally to develop other projects and provided to the market as a product
  - Worked as Project Lead, designed the architecture of the system, which used PostgreSQL RDBMS, a modified Spring Boot as the back-end framework, and Vue.js as the front-end framework
  - Coordinated a team of around 4 people to develop the functions of the system and performed code reviews regularly
  - Supported custom data sources, including:
    - files
    - other RDBMS such as MySQL and Oracle
    - external web APIs
  - Supported customization of data after retrieved from remote sources for local front-end processing
  - Allows access control based on roles to allow customized content segeration between users
  - Enables spatial and non-spatial data visualization in 2D and 3D maps
  - Can display large amount of data while ensuring user experience, can keep 60 fps in WebGL environment.
- Internal web map API
  - A front-end web map API written in pure JS that supported web mapping libraries such as Openlayers and Cesium.JS
  - Worked as project lead, designed the architecture of the API, and created an easily extendable system structure that allows incorporating new libraries if needed.
  - Optimized the performance of map functions using WebGL and increased the performance of rendering multiple features by 200%, compared to the previous implementation.
  - Implemented a large variaty of data visualization effects, such as
    - 3D heatmap
    - Volumetric cloud
    - Display of large 3D models on map
  - Powered the MapGIS-Board project and other map related projects in the company
- Field Survey App
  - Android app used by Data Engineering team of the company, used in their task of surveying buildings
  - Used Spring Boot for back-end, Cordova for front-end, wrapped into an Android app
  - Originally used Oracle for database, later migrated to PostgreSQL
  - Support import/export from/to ESRI .shp format
  - Enabled surveyors of the company to complete tasks effectively and reduced their work load by around 50%

## Guangzhou Subtropical Building Laboratory, South China University of Technology

- Guangzhou Historical Street Study
  - Gathered frequency of keyword search occurence data from Baidu, a search engine in China. Gathered data for more than 100 keywords.
  - Digitization of Guangzhou's historical street data from old maps into ESRI shapefiles using ArcGIS.
  - Data analysis and display of gathered data in Python using ArcPy.
