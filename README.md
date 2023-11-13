# RC-UW_ResearchLog
Log of weekly research accomplishments

November 05 - November 11
Research Ideas:
- Lateral circulation at mouth of Willapa River and Chehalis River (affects H101 and H105)
  - Motivation: Observe/model momentum budget at bends at mouth to look at bank erosion or salt transport
    - Compare between WB and GH
  - Would require instruments put out and bathymetry survey
    - NCEI has 1/3 arc second (10m) resolution DEM for Willapa Bay (stops just west of Raymond)
    - GH: https://catalog.data.gov/dataset/grays-harbor-p280-bathymetric-digital-elevation-model-noaa-nos-estuarine-bathymetry
	- Updated 11/12/2020 (1/3 arc second)
  - How does ebb/flood tides for stratified/unstratified flows affect the energy at the bends?
    - Is it asymmetrical or symmetrical? (Primary, secondary flows that can affect erosion)
    - https://journals.ametsoc.org/view/journals/phoc/49/6/jpo-d-18-0175.1.xml
    - https://journals.ametsoc.org/view/journals/phoc/52/7/JPO-D-21-0298.1.xml
      - Modeled
    - https://www.sciencedirect.com/science/article/abs/pii/S027843431300126X
    - https://people.duke.edu/~jlh82/pubs/Nidzieko_et_al_2009_JPO.pdf
    - https://scholarcommons.sc.edu/cgi/viewcontent.cgi?article=1046&context=geol_facpub
- Model vertical structure at mouth of rivers during storm events (compared to normal ebb/flood tides)
- Look at time lag between Tokepoint station and Willapa River gauge (east of Raymond)

## October 29 - November 04
- Loaded new Delft3D-FM license onto laptop.
- Updated Laptop (took ~2 days).
- Completed first three tutorials (creating a curvilinear grid and creating a triangular grid and Coupling multiple separate grids).
- Researched Delft FM studies on land boundaries (in Notion "Delft FM Studies" doc).
- Found historic highs for stream gauges in Grays Harbor and Willapa Bay.
- Found FEMA flood zone maps for Grays Harbor county (updated 2020).

## October 22 - October 28
- Created temporary directory on hyak (/mmfs1/gscratch/derakhti/rchiu18).
- Worked with Christie on HYAK basics (main files for Delft3D model run, submitting job, cancelling job, checking storage allocation, etc).
- Tested rsync from HYAK server to local machine.
- Requested new license key to renew DelftFM license on Alex's laptop.

## October 15 - October 21
- Created Git repository on HYAK account for DelftFM files.
- Read through Hydrodynamic section in Delft-FM manual.
- Tried to understand SLURM scripts.
- Attempted to understand 'D3DSUPDUSA-252 - Decreased Flow performance during parallelization with waves' gmail thread.

To Do:
- Attempt to create a test container and test SLURM job
    - https://hyak.uw.edu/docs/hyak101/python/syllabus
- Work on examples in Delft3D program

## October 08 - October 14
- Meet with Christie to discuss Deflt3D basics - (10/09)
- Create shared spreadsheet for monitoring stations in Willapa Bay, Grays Harbor, and surrounding area.
  - https://docs.google.com/spreadsheets/d/1Mqzt7Lxn9V12FRSPelFWJJG9nrxQnFr4MR76eoNUSmU/edit#gid=0
- Research more into Delft-FM architecture and tools.
  - Begin reading Delft-FM manual (https://content.oss.deltares.nl/delft3d/D-Flow_FM_User_Manual.pdf)

![Delft3D Diagram](Figures/Delft3D_diagram.png)

- General research ideas for dissertation:
  - ADCP/water level gauges at mouth of Willapa River.
    - Measure propagation of waves after shoal at bay mouth.
      - Time lag for wave propagation.
    - Investigate hydrodynamics that dampen/amplify inflow/outflow at mouth.
      - Flow gauge is located east of Raymond.
    - Look at velocity profiles during peak and after during relaxation to observe any density driven flows/circulation from interaction between ocean inflow and freshwater outflow.
  - Water level gauges at Nahcotta Port (potential outwash/overtopping investigation).
  - Lidar survey of waves and beach evolution, wave behavior over the shoal? during storm events.
    - Wave run up, set up, to infer ebb shoal migration placement and migration.
