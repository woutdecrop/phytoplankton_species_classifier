# Phytoplankton_species_classifier
[![Build Status](https://jenkins.indigo-datacloud.eu/buildStatus/icon?job=Pipeline-as-code/DEEP-OC-org/UC-woutdecrop-phytoplankton_species_classifier/master)](https://jenkins.indigo-datacloud.eu/job/Pipeline-as-code/job/DEEP-OC-org/job/UC-woutdecrop-phytoplankton_species_classifier/job/master)



To launch it, first install the package then run [deepaas](https://github.com/indigo-dc/DEEPaaS):
```bash
git clone https://github.com/woutdecrop/phytoplankton_species_classifier
cd phytoplankton_species_classifier
pip install -e .
deepaas-run --listen-ip 0.0.0.0
```
The associated Docker container for this module can be found in https://github.com/woutdecrop/DEEP-OC-phytoplankton_species_classifier.

## Project structure
```
├── LICENSE                <- License file
│
├── README.md              <- The top-level README for developers using this project.
│
├── requirements.txt       <- The requirements file for reproducing the analysis environment, e.g.
│                             generated with `pip freeze > requirements.txt`
│
├── setup.py, setup.cfg    <- makes project pip installable (pip install -e .) so
│                             phytoplankton_species_classifier can be imported
│
├── phytoplankton_species_classifier    <- Source code for use in this project.
│   │
│   ├── __init__.py        <- Makes phytoplankton_species_classifier a Python module
│   │
│   └── api.py             <- Main script for the integration with DEEP API
│
└── Jenkinsfile            <- Describes basic Jenkins CI/CD pipeline
```
