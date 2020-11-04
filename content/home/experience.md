+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Research Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
# date_format = "Oct 2020"

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
  description = """
  > **Variational Autoencoder algorithm in resting state fMRI data.
  * Extracted code was used to do individual identification (as brain ID). K-means clustering is performed to analyze brain patterns reflected by latent space. 
  * Extend the data from 2D fMRI data to 3D fMRI data. 3D data contains white matters. I analyzed latent code considering 'channel bandwidth' to see the non-informative latent variable and informative variable in VAE model.
  > **Neural Ordinary Differential Equation for temporal dynamic model.** 
  * I model the temporal dynamic of resting state fmri data as ordinary differential equation, and analyze the saddle point for latent of latent code. This method brings a new view for spatial temporal modeling compared to existing method like AR model and HMM. """

[[experience]]
  title = "Graduate Researcher"
  company = "University of Michigan, Ann Arbor"
  company_url = ""
  location = "MI"
  date_start = "2019-09-01"
  date_end = "2019-12-31"
  description = """
  > **Reconstruction on SPECT data.** **[demo](https://codernomercy.github.io/elements.html)**.
  * Constructed Convolutional Neural Network by Keras in Python to compress and reconstructed SPECT image’s projection. Explored low rank property of SPECT projection. Analyzed several metrics of reconstruction like NRMSE, Contrastive Rate, Contrastive to Noise Ratio. """

[[experience]]
  title = "Undergraduate Researcher"
  company = "UESTC"
  company_url = ""
  location = "China"
  date_start = "2018-07-01"
  date_end = "2019-07-01"
  description = """
  > **Intelligent Communication.**
  * Used Neural network to replace computation costing part of BiG-AMP which is used in image reconstruction. 
  > **Matrix Factorization** **[code](https://github.com/CoderNoMercy/BIG-AMP-improvement-trial)**
  * Studied the Bilinear Generalized Approximate Message Passing algorithm and designed Variational Bayesian to improve the accuracy. Utilized Matlab to simulate the algorithm and compared the two algorithms in the same condition."""

+++
