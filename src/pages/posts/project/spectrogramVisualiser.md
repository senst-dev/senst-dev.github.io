---
layout: ../../../layouts/ProjectPostLayout.astro

title: 'SpecVis'
description: 'A webapp for creating spectrograms '
gh: https://github.com/senst-dev/SpecVis
image:
    filepath: '/src/images/projects/spectrogramVisualiser.png'
    alt: 'A screenshot of the SpecVis app, showing a spectrogram (a visual representation of sound) and the python code to generate it.'
---

## What is it?
SpecVis is a web app for trying out Python spectrogram creation libraries - it uses a Flask backend and small React frontend. A user can upload a .wav file, or use a default file and then it creates a visual representation of this sound (3D graph of Frequency vs Time, with color representing Intensity). Users can change some parameters, the library used, and whether axes are included. It returns the image of the spectrogram, but also the code that can be used to generate it!

## But why?
During my Part IV project at Uni, was working on a machine learning based approach for dysarthria intelligibility assessments ([published paper here btw 😉](https://link.springer.com/article/10.1007/s12559-022-10041-3)). As a TL;DR summary - turn audio files into an image, then perform image classification to detect a level of speech pathology.

A lot of the work here involved getting the right spectrograms generated. So reasoning here was a small app that could be used to try out some different configurations for rapid iteration and then just copy the code over as part of pipelines to generate train/test data.

## What's next
- No longer working free on Heroku, so finding an alternative hosting option.
- Adding some extra options for customization options.