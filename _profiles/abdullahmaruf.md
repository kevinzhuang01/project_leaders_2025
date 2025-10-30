---
layout: profile
name: Abdullah Maruf
organization: Dartmouth College
department: Engineering
project_title: 'From MPI to ZeroMQ: Scalable Online Feedback for Serial Crystallography
  with Bayesian/ML-Ready Hooks'
status: Accept (Confirmed)
abstract: 'OM (OnDA Monitor) is widely used at free-electron laser and synchrotron
  facilities for online scoring and monitoring of diffraction during serial crystallography.
  We present a re-architected parallelization layer that replaces the original MPI
  layer with a ZeroMQ (“ZMQ-socket”) design that reduces external dependencies, improves
  portability across heterogeneous beamlines, and enables dynamic worker join/leave
  so monitoring can resume after interruptions without loss of accumulated statistics.
  Beyond these systems gains, we expose a lightweight probabilistic interface that
  supports Monte Carlo adaptation in the small-hit regime: sequential sampling updates
  run-time estimates of hit rate and resolution, tunes acquisition/processing thresholds,
  and provides uncertainty-aware stopping/continuation decisions to use beamtime efficiently.
  The core remains usable out-of-the-box, while optional plug-ins can ingest streaming
  features for complementary deep-learning quality scoring. Ongoing work targets optimization
  of the ZMQ layer and benchmarking Monte Carlo policies under realistic beam conditions,
  toward a portable release for routine deployment at beamlines.'
academic_interests: My research interests focus on computational modeling and software
  development to support scientific discovery across materials science, planetary
  exploration, and high-energy experiments. I have worked on quantum simulation tools
  to study materials under extreme conditions, such as those that could inform future
  space missions by providing insights into planetary regolith and high-pressure compounds.
  This has built my experience in creating reliable computational frameworks that
  connect theory with real-world applications. I also pursue improvements in software
  for experimental settings, like the OM (OnDA Monitor) framework used in serial X-ray
  crystallography at synchrotrons and free-electron lasers. Here, I have implemented
  socket-based parallelization to enhance portability, reduce dependencies, and allow
  dynamic resumption after interruptions, maintaining key statistics. In future work,
  I plan to integrate neural network models – such as convolutional neural networks
  for pattern recognition in diffraction data and graph neural networks for structural
  analysis – alongside Bayesian optimization for parameter tuning and Monte Carlo
  methods for uncertainty assessment. With a drive to learn and explore, I aim to
  contribute to tools that advance structural biology and materials research, always
  seeking collaborative ways to make science more efficient.
email: abdullah.al.maruf.gr@dartmouth.edu
citizenship_status: F-1 Visa
academic_status: Doctoral Student
additional_comments: 'Co-Author – Generalized Mixup Model (submitted at a conference):
  https://github.com/Maruf001/generalized_mixup_model/blob/main/From%20Confusion%20to%20Clarity%20%E2%80%93%20Generalized%20Mixup.pdf
  Top Contributor – OM Software for beamline data processing (in-real time): https://github.com/omdevteam/om
  Google Scholar: https://scholar.google.com/citations?hl=en&user=SxrfWkIAAAAJ'
website: https://github.com/Maruf001
image: "/assets/images/profiles/Letter-Number-Files/abdullah_maruf_1.png"
---

## Academic Interests

My research interests focus on computational modeling and software development to support scientific discovery across materials science, planetary exploration, and high-energy experiments. I have worked on quantum simulation tools to study materials under extreme conditions, such as those that could inform future space missions by providing insights into planetary regolith and high-pressure compounds. This has built my experience in creating reliable computational frameworks that connect theory with real-world applications. I also pursue improvements in software for experimental settings, like the OM (OnDA Monitor) framework used in serial X-ray crystallography at synchrotrons and free-electron lasers. Here, I have implemented socket-based parallelization to enhance portability, reduce dependencies, and allow dynamic resumption after interruptions, maintaining key statistics. In future work, I plan to integrate neural network models – such as convolutional neural networks for pattern recognition in diffraction data and graph neural networks for structural analysis – alongside Bayesian optimization for parameter tuning and Monte Carlo methods for uncertainty assessment. With a drive to learn and explore, I aim to contribute to tools that advance structural biology and materials research, always seeking collaborative ways to make science more efficient.

