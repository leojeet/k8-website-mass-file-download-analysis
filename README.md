# k8-website-mass-file-download-analysis


This project is intended to create a service that will analyze a setof a sigle or batch of files to be processed by the GlassWall engine to detect any potential threats. After the analisys takes place the result will be an xml. 

## Workflow
- A list of files will be selected.
- GlassWall engine will be called to analyze all files selectec.
- The xml output will be put on a storage service.
