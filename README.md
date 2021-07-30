# Clustering Earthquake Waveforms

Earthquakes are normally labeled by source types, magnitudes, and intensities. In this project, we will explore the use of machine learning methods to cluster earthquake waveforms. The goal is to create a library of earthquake waveforms or composite waveforms that could represent the main characteristics after clustering. We will also seek quantitative descriptions of the clusters.

This project is motivated by the need for representative earthquake waveforms in earthquake detection through template matching. Template matching or matching filtering method has been used in detecting earthquakes from continuous seismic records. However, how to find the most representative and complete library of templates is yet not well resolved. One way is to use the entire earthquake catalog from previous years as templates, though the computational time will be large. In addition, there are similar waveforms in the catalog earthquake waveforms, which would result in redundancy in computing. Manually inspecting the earthquake waveforms and selecting a subset of them as templates would significantly decrease the computational time. However, how to ensure the completeness of the template library is very important. This project tries to solve this issue by creating representative clusters of earthquake waveforms.
