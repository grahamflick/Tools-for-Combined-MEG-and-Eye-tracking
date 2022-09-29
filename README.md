# MEG-EyeTracking
This repository holds tutorial scripts developed for the MEG and Neuroscience of Language Lab's Methods Meetings in April 2022.

There are two primary Jupyter notebooks that illustrate how to make experimental stimuli and process conrurrent MEG and eye-tracking data.

1. MakeStimuli.ipynb
This notebook illustrates how to load in a .csv file containing experimental stimuli (e.g., sentences) that you want to display and construct images with those stimuli laid on top of a background. It also demonstrates how to output individual python dictionary objects defining the bounding boxes of each word within each image, defined in screen pixel coordinates, and overlay those bounding boxes on the stimuli as a quality assurance check.

2. ProcessEyeLinkData.ipynb
This notebook walks through how to load in a .ascii file from the SR Research Eyelink system (converted from .edf with the developer tools function edf2asc), extract relevant events, generate summary statistics, overlay fixation patterns on stimuli images, and use the timing of eye movement events to define fixation-related responses in continuous MEG data.

This repository is under continuous development.
