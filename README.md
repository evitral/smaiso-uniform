# smaiso-uniform

The purpose of the sma-dft project is to study the evolution of an interface between a smectic-A liquid crystal and a isotropic phase. The present files contain an implementation of the models proposed in:

(1) E. Vitral, P.H. Leo, J. Viñals, Physical Review E 100.3 (2019)

These are custom C++ codes based on the parallel FFTW library and the standard MPI passing interface. Part A was the initial study of a smectic-A in contat with its isotropic phase of same density, describing a diffusive evolution of the interface without advection, whose results are found in Ref. (1).


## A. no-adv: smectic-iso, advection is off, uniform density

A1. cosNoAdvConics.cpp

A2. cosNoAdvTrackBump.cpp

A3. cosNoAdvTrackMult.cpp

A4. cosNoAdvTrackSing.cpp
