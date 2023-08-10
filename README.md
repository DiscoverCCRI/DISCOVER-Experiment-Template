# DISCOVER Experiment Template
A template repo for DISCOVER experiments that users may fork or reference when creating experiments. Each experiment should follow this template for the highest chance of success when submitting to the DISCOVER infrastructure.

Each experiment should:

1. Be formatted as a GitHub repository based on this template.
2. Have a designated location for receiving experiment results, such as a shared Google Drive folder.

Once you submit an experiment, it will be transformed into a simple Docker application to help with experiment management and maintenance on the DISCOVER infrastructure. For this to work well, it's prudent to have detailed build and run instructions in your README.

If you are new to GitHub, we have compiled some helpful steps to get you started: [Usage Guide for DISCOVER Template Repo](USAGE.md)

---

All code files should be stored in the `src/` folder and the primary execution file should be located in `src/main.py`. Please use the following outline as a guide for setting up your experiment repo README.

# Experiment Name
Provide a description for what your experiment is trying to do.

# Installation
Detail instructions and build commands for installation.

# Run
Provide instructions on how to run your application.

# Results
Provide a cloud storage link for the DISCOVER Operator to upload your experiment results. This should also be included in the experiment details on the DISCOVER portal. Google Drive works well for this, just be sure to share it with anyone who has access to the link of your shared folder.

To see this template applied to an actual experiment, check out the branches associated with this repository:
 - [RoverDemo experiment](https://github.com/DiscoverCCRI/DISCOVER-Experiment-Template/tree/RoverDemo)
