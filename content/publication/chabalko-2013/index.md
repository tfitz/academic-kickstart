+++
title = "GPGPU implementation and benchmarking of the unsteady vortex lattice method"
date = 2013-01-01
authors = ["C. Chabalko", "T. Fitzgerald", "B. Balachandran"]
publication_types = ["1"]
abstract = "The unsteady vortex lattice method is widely known for its robustness in modeling inviscid flow fields and aerodynamic loading.  This method can be used to model a variety of configurations including multiple flapping wings in unsteady flows.  One of the key computational algorithms used in this model can be expressed as nested loops or as a linear algebra based matrix vector product.  Both forms are compared, and several different implementations including Matlab, C, and a GPGPU version are compared.  The GPGPU based implementation is faster than the Matlab implementation by almost three orders of magnitude, and faster than the C implementation by almost two orders of magnitude.  Details of the implementation are provided.  The linear algebra implementation is determined to consume excess memory without a corresponding increase in computation performance.  The fastest GPGPU implementation is applied to the study of ground effect, and separately, to the roll up of a vortex filament.  Each of these cases would be intractable to compute without the acceleration offered by the GPGPU."
featured = false
publication = "*51th AIAA Aerospace Sciences Meeting*"
doi = "10.2514/6.2013-288"
+++
