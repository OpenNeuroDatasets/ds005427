# README

## Access to the Data

### Contact Person
For additional information, please contact:
- Carsten Murawski, carstenm@unimelb.edu.au
- Pablo Franco at jpfranco@unimelb.edu.au

## Overview

### Project Name
The Neural Dynamics Associated with Computational Complexity

### Year(s) the Project Ran
Data acquisition happened between October 2017 and February 2018. 

### Brief Overview of the Tasks in the Experiment
The experiment aimed to investigate the neural processes associated with solving computationally complex problems, specifically focusing on the 0-1 knapsack problem, a combinatorial optimization problem. Participants solved several instances of this problem while undergoing ultra-high field (7T) functional magnetic resonance imaging (fMRI). The instances varied in computational hardness, and the study aimed to characterize the neural dynamics as a function of computational complexity.

### Description of the Contents of the Dataset
The dataset includes a structural MRI image (T1w) and BOLD data from 20 participants. The BOLD dataset was collected while participants performend the knapsack decision task.

### Independent Variables
- **Typical-Case Complexity (TCC)**: High vs. Low
- **Satisfiability**: Satisfiable vs. Unsatisfiable

### Dependent Variables
- **Behavioral Performance**: Accuracy of the responses in the knapsack decision task.
- **Neural Activation**: BOLD signal changes measured via fMRI.

### Control Variables
- **Subject Pool**: Right-handed volunteers aged 18-35 years.
- **Environmental Conditions**: Experiments conducted in a controlled MRI environment.
- **Task Setup**: Standardized instructions and practice sessions before the actual task.

### Quality Assessment of the Data
The quality of the fMRI data was ensured through preprocessing steps including motion correction, slice-time correction, and normalization.

## Methods

### Subjects
- **Subject Pool**: 20 right-handed volunteers from Melbourne University and the surrounding community (14 female, 5 male, 1 other; age range = 18-35 years, mean age = 26.6 years).
- **Inclusion Criteria**: Minimum age of 18 years, maximum age of 40 years, right-handedness.

### Apparatus
The experiment was performed using a 7 Tesla Siemens MAGNETOM scanner with a 32-channel radio frequency coil. The BOLD signal was measured using a multiband echo-planar imaging sequence.

### Initial Setup
Participants filled out an MRI screening form, read a plain language statement, provided written informed consent, and completed a practice session of the knapsack decision task before going into the scanner.

### Task Organization
Participants performed the knapsack decision task inside the scanner and a set of complementary tasks outside the scanner, including the knapsack optimization task and cognitive function tasks from the CANTAB battery. The order of tasks was standardized across participants.

### Task Details
- **Knapsack Decision Task**: In each trial, they were shown a set of items with different values and weights, as well as a capacity constraint and a target profit. Participants had to decide whether there exists a subset of those items for which (1) the sum of weights is lower or equal to the capacity constraint and (2) the sum of values yields at least the target profit. Participants solved 56 instances of the (0-1) knapsack decision problem, presented in a randomized order. Each trial consisted of an items stage (3 seconds), solving stage (22 seconds), response stage (2 seconds), and a jittered inter-trial interval (8-12 seconds).

### Additional Data Acquired
Behavioral data from the knapsack optimization task and cognitive function assessments were collected.
- **Knapsack Optimization Task**: Participants were asked to find a subset of items that maximized total value subject to a capacity constraint. They solved a totla of 18 instances of the problem and had up to 60 seconds to solve each instance. 
- **Cognitive Function Tasks**: Included Reaction Time (RTI), Paired Associates Learning (PAL), Spatial Working Memory (SWM), and Spatial Span (SSP) from the CANTAB battery, as well as a mental arithmetic task.

### Experimental Location
The experiment was conducted at the Melbourne Brain Centre, Parkville, Victoria, Australia.

### Missing Data
No participants or trials were excluded from the data analysis of the knapsack decision task. 

## Notes
- Additional data collected and the paradigm are available at the Open Science Framework (OSF): [https://osf.io/g4h7y/](https://osf.io/g4h7y/).
- Additional information about the experiment is available in the associated manuscript [here](https://www.biorxiv.org/content/10.1101/2022.01.05.475102v1).