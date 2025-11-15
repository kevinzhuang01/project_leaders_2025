---
layout: profile
name: Tianyi Shi
first_name: Tianyi
last_name: Shi
email: tianyishi@lbl.gov
institution: Lawrence Berkeley National Laboratory
biography: Tianyi Shi is a postdoctoral scholar at Lawrence Berkeley National Laboratory
  in the Scalable Solvers Group within the Computing Sciences Area. He received his
  Ph.D. in Applied Mathematics from Cornell University. Tianyi’s research focuses
  on developing efficient and scalable algorithms for sparse and data-sparse matrices
  and tensors, with applications in computational chemistry and high-performance computing.
  His work involves designing shared- and distributed-memory parallel CPU and GPU
  codes in C, C++, and CUDA, and conducting large-scale experiments on supercomputers.
project_title: Develop tensor algorithms in Python
topical_areas: Applied Computer Science; Applied Mathematics; High Performance Computing;
  Open Source Software
abstract: A wide range of applications involve multidimensional data as observations
  or solutions, and these data sets are often referred to as tensors. The storage
  cost of tensors grows exponentially with respect to the dimensionality, also known
  as "the curse of dimensionality", so researchers develop various data-sparse tensor
  formats for lower storage and faster computations. This project focuses on a special
  tensor format called the tensor-train (TT) format. We have developed some data-centric
  algorithms to factor a given tensor into TT representations. Our proposed algorithms
  can also be parallelized, and we can use them in analyzing large data sets, solving
  partial differential equations, and conducting statistical learning. In order to
  compare with state-of-the-art data-centric TT decomposition packages, we would like
  to implement our algorithms in Python, specifically with PyTorch and MPI4Py, using
  highly optimized linear algebra kernels and distributed memory parallelism. Then
  we can perform a thorough comparison between our proposed algorithms and the existing
  ones.
desired_skills: 'Interests or background in numerical linear algebra and parallel
  computing. Desired skills: know how to code in Python, preferably PyTorch.'
lightning_talk_title: Tensor Computations in Python
keywords: Numerical linear algebra; tensor computations; parallel algorithms; Python.
---
