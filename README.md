# DEPRECATED, Everything moved to https://github.com/ckury/uconn-sentiment-backend

# Sentiment Project Automation
This repository holds all of the files and code for scripts used to automate the scoring process on Google Cloud Compute Engine. Note that this does not include any of the actual scoring and calculating, only file/data downloads, environment preparation, activating the scoring program, weighting, and summary programs, datastore upload, and environemnt cleanup. Note that this is intended to run on a Spot/Preemptive VM (a virtual machine that is at a heavily reduced cost in exchange for the potential of the machine being prematurely shutdown) and thusly has logic to handle a preemption if one occurs (not currently functional).
