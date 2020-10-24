+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Research Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Research Assistant"
  company = "University of Michigan, Ann Arbor"
  company_url = ""
  location = "MI"
  date_start = "2020-05-01"
  date_end = ""
  description = """I did two project this summer including: 1. Used Variational Autoencoder algorithm to get disentangled latent code from pre-processed resting state fMRI data. Extracted code was used to do individual identification (as brain ID). K-means clustering is performed to analyze brain patterns reflected by latent space. I also extend the data from 2D fMRI data to 3D fMRI data. 3D data contains white matters. I analyzed latent code considering 'channel bandwidth' to see the non-informative latent variable and informative variable in VAE model.
2. Took advantage of Neural Ordinary Differential Equation method to establish temporal dynamic model for resting state fMRI data. I analyze the saddle point for latent of latent code. This method brings a new view for spatial temporal modeling compared to existing method like AR model and HMM.
"""
  # Responsibilities include:
  
  # * Analysing
  # * Modelling
  # * Deploying
  """

[[experience]]
  title = "Graduate Researcher"
  company = "University of Michigan, Ann Arbor"
  company_url = ""
  location = "MI"
  date_start = "2019-09-01"
  date_end = "2019-12-31"
  description = """Constructed Convolutional Neural Network by Keras in Python to compress and reconstructed SPECT image’s projection. Explored low rank property of SPECT projection. Analyzed several metrics of reconstruction like NRMSE, Contrastive Rate, Contrastive to Noise Ratio."""

+++
