[Back to the projects list](../../)

<!-- For information on how to write GitHub .md files see https://guides.github.com/features/mastering-markdown/ -->

# Incorporate motion correction techniques into SpkeInterface

## Key Investigators

- Alessio Buccino
- Samuel Garcia
- Ben Dichter
<!-- - Investigator 1 (Affiliation)-->
<!-- - Investigator 2 (Affiliation)-->

## Project Description


Motion of the probe has been a major impediment to high quality spike sorting on high density probes such as the Neuropixel probe. Recent developments in preprocessing have displayed promising results for solving this issue, but these algorithms are varied, complex, and multi-step. Here, we are incorporating these motion correction methods into SpikeInterface so that they are easier for users to access. The motion correction process can be summarized in the following steps: 

Using action potentials:
1. detect peak
2. localize peaks
    1. center of mass
    2. monopolar triangulation
3. motion estimation
    1. rigid or non-rigid
    2. decentralize
    3. motion cloud


Using LFP:
...
## Objectives

Incorporate the following methods into SpikeInterface
* [ ] detect peaks
* [ ] localize peaks/center of mass
* [ ] localize peaks/monopolar triangulation
* [ ] motion estimation/rigid decentralize
* [ ] motion estimation/non-rigid decentralize

Each of these methods requires implementation, testing, and documentation of usage.

## Approach and Plan

1. Create/refine motion correction map [here](https://docs.google.com/drawings/d/1igJuCqULG7lNq4TfOSNr351Fm03lbeddXLA9Ev77bTA/edit).
<!-- 1. Describe the steps of your planned approach to reach the objectives.-->
<!-- 1. ... -->
<!-- 1. ... -->

## Progress and Next Steps

Motion correction map: https://docs.google.com/drawings/d/1igJuCqULG7lNq4TfOSNr351Fm03lbeddXLA9Ev77bTA/edit

<!--Populate this section as you are making progress before/during/after the hackathon-->
<!--Describe the progress you have made on the project,e.g., which objectives you have achieved and how.-->
<!--Describe the next steps you are planing to take to complete the project.-->

## Materials

* https://spikeinterface.github.io/blog/spikeinterface-motion-estimation/
<!--If available add links to the materials relevant to the project, e.g., the code generated for the project or data used-->
<!--If available add pictures and links to videos that demonstrate what has been accomplished.-->
<!--![Description of picture](Example2.jpg)-->

## Background and References

See initial progress [here](https://spikeinterface.github.io/blog/spikeinterface-motion-estimation/)

<!--Use this space for information that may help people better understand your project, like links to papers, source code, or data ,e.g:-->
<!-- - Source code: https://github.com/YourUser/YourRepository -->
<!-- - Documentation: https://link.to.docs -->
<!-- - Test data: https://link.to.test.data -->

