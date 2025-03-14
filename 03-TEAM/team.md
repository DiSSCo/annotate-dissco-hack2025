# OntoGPT Machine Annotation Service

The idea of this project is to annotate information from the DiSSCover platform using OntoGPT to extract ontologies.

## Steps:

### 1. Setup OntoGPT
- Install and explore how OntoGPT works.
- Reference: 
  - [OntoGPT Repository](https://github.com/monarch-initiative/ontogpt)
  - [OntoGPT Documentation](https://monarch-initiative.github.io/ontogpt/)
  - [OntoGPT-BioHackathon Repository](https://github.com/RajapreethiRajendran/ontoGPT-BioHackathon)

### 2. Develop & Deploy OntoGPT as an Application
- Currently, we have OntoGPT templates to extract ontology for habitat information: [OntoGPT-BioHackathon](https://github.com/RajapreethiRajendran/ontoGPT-BioHackathon). Feel free to explore with your own use case.
- Develop and host OntoGPT as an application with an API endpoint.
- The API will be called by MAS wrappers.
- Deploy the OntoGPT application in our own infrastructure.

### 3. Develop MAS Wrappers
- Build MAS wrappers based on existing templates: [MAS Template](https://github.com/diSSCo/machine-annotation-service-template).
- Reference example: [Demo Enrichment Service](https://github.com/DiSSCo/demo-enrichment-service-image).
- The DiSSCo core team will deploy these wrappers into the **DiSSCo infrastructure**.

### 4. Testing & Further Exploration
- The setup can be tested and explored further.
- Happy hacking!

