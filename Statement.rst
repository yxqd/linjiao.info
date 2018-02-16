.. _statement:

Research Statement
==================

Introduction
------------

My research focus is on developing high-performance computational
tools for physical sciences.
I am also working on applying these computating tools for research on
developing materials probes based on scattering physics, 
including diffractometry and spectrometry and for
applications of these techniques.

At this moment, I am the project leader of VNF, 
the Virtual neutron facility (http://vnf.caltech.edu),
a product of the DANSE project, 
a National Science Foundation (NSF) software development endeavor 
on distributed data analysis for neutron scattering experiments.  
This DANSE project is in parallel with the construction of the 
`Spallation Neutron Source (SNS) <http://www.sns.gov>`_ in 
the `Oak Ridge National Lab <http://www.ornl.gov>`_, Tennessee, 
which let U.S. take the lead in the world in providing the most intense
pulsed neutron beams to be used as probes of materials, molecules, 
and condensed matter, for both scientific research and industrial development.  

The `Virtual Neutron Facility (VNF) <http://vnf.caltech.edu>`_,
is a
ground-breaking software project that provides a powerful,
flexible, integrated computing environment that makes
complex material simulations and neutron scattering experiment
simulations as simple as a few mouse-clicks.
As a result, the VNF web service will enable much more elaborate data
analysis for neutron scientists. 

I am also the author of the `luban <http://lubanui.org>`_,
a general-purpose user interface "language", which makes it
much easier to develop rich, interactive user interface.
Luban could benefit many other high-performance computing software
projects.

In my earlier academic career, I also worked on
Mossbauer diffractometry.

Following are the research topics I am interested in and contributing:


High-performance scientific-computing
-------------------------------------

I started in the summer of
2004 to work on the DANSE project, which is an effort to
facilitate easy data analysis for the next generation neutron source
in the United States – SNS (Spallation Neutron Source). SNS is now
producing the most bright neutron beams in the world. This effort
takes advantage of rapid developments of computer hardware and
software seen in the past few decades, to organize existing data
analysis codes together into one framework, and also develop new
algorithms for data analysis. This effort intends to keep the
computational capacity of neutron science community up to speed with
the huge advance of neutron beam brightness. 


Virtual neutron facility
!!!!!!!!!!!!!!!!!!!!!!!!

I am leading the effort to develop VNF in the DANSE project, 
`the virtual neutron facility <http://vnf.caltech.edu>`_. 
The Virtual Neutron Facility is a web application that allows users to
easily perform sophisticated simulations of materials and 
neutron experiments. Users can, just like in a real neutron
facility, prepare sample, and put sample in a neutron instrument,
and start measureing neutron data. After virtual experiments,
simulated neutron data can be analyzed and compared to real
data to gain insights of structures and dynamics in materials.

Scientists have been hoping to use full simulation of an experiment to
recover physics properties of materials in data analysis. 
The conventional way of data analysis is called data reduction.  
It starts from detector data, and by rebinning the data and making
several corrections, ends up with data close to physical models. 
This route of data analysis, however, could be faulty in more
sophisticated cases of samples. 
The “corrections” are ways to try to deconvolute instrument parameters
from raw data, 
but such deconvolution is “dangerous” with more complicated sample and
sample arrangement, 
meaning it could lead to incorrect explanation of data. 
A good way to overcome this problem is to perform full Monte-Carlo
simulation of neutron experiments and directly compare the simulated
detector data to real detector data,
in order to recover the physics models of the interested sample. 

These simulations tend to be difficult and take long time. It also
takes a great deal of expertise to get those simulations right.
VNF makes this kind of sophisticated computation and analysis easy,
and available to much broader science community.
It "records" the expertise of material-simulation/neutron-scattering-simulation
professionals in the form of computer programs so that
normal users can use those computing tools; it also
make a vast amount of computing resource available by using
distributed computing techniques.

VNF is a highly-integrated, easy-to-use, yet flexible and powerful
computing environment.
I am responsible for the
design and implemenation of its infrastructure and its
key features.


MCViNE
!!!!!!
http://docs.danse.us/MCViNE


luban
!!!!!
I am the author of the `Luban <http://lubanui.org>`_ ,
a software product that can greatly enhance
the user interactivity of scientific software packages.

Developing user interface for software is hard. Developing a good user
interface that is easy to use for novice users, yet flexible and
powerful
enough for advanced users is harder. 
Many user interface tools exist but most of them,
when used, lead to convoluted and unmaintenable code.

Developing web user interface is harder than developing normal desktop
UI, 
due to specifics of web langauges such as html and javascript.

The Luban package provides a generic way of specifying the content (no
detailed layout, no styles, no color or sizes etc) of user interfac
(UI) as a hierarchy of UI elements. The representation is so generic
that user interfaces on different “media” (web, native, or ...) can be
rendered from this representation using different “weavers”. The
layout and styles will be specified by style sheets (or similar
mechanisms).

The Luban package also provides a generic way to describe “actions” on
to accompany the UI elements. Those actions are rendered by weavers to
codes that can be executed to manipulate the UI elements, or talk to
the UI controller. 

In essence, Luban provides an abstraction layer for user interface
building, so that developers of user interfaces can leverage luban’s
rendering engines (which are extendable) to create sophisticated user
interfaces using simple python calls.

The `luban <http://lubanui.org>`_ package is now in use by 
the VNF project, and could be useful for many other 
high-performance scientific-computing projects.



DrChops
!!!!!!!



Mossbauer diffractometry
------------------------

During my doctoral research under the guidance of
`Dr. Brent Fultz <http://www.its.caltech.edu/~matsci/btf/Fultz1.html>`_,
I worked on Mossbauer diffractometry, a pioneering project that
combines the superb capability of Mossbauer spectrometry to probe
short-range order structures (local chemical environments) and the
capability of diffractometry to probe long-rang order structures. 

Diffraction techniques have made numerous great contributions to
science.  Fifteen Nobel prizes have been awarded to
diffraction-related research.  Mossbauer effect, once discovered in
1955-1957 by Rudolf Mossbauer, found wide applications in various
fields ranging from relativistic physics, nuclear physics, chemistry,
materials sciences involving superconductor, magnetic materials,
metals, all the way to biology, and even archeology. The importance of
this effect was realized so quickly that Rudolf Mossbauer won Nobel
Prize in 1961, only four years after the publication of his work.


The idea of Mossbauer powder diffractometry is simple: the capability
of diffractometry is combined with the capability of Mossbauer
spectrometry then we have a technique that can detect long-range order
of atoms with specific short-range order.  This technique will see
various applications, including (but not limited to) defect structure,
magnetic structure, quasi-crystals, superconductors, etc., in
materials science. It is also expected to be useful to biology, for
example, on proteins for nitrogen fixing.  




My ongoing and proposed research
--------------------------------

The research I presently
perform at the
`Caltech Center for Advanced Computing Research (CACR) <http://www.cacr.caltech.edu>`_,
Division of applied
sciences and engineering, California Institute of Technology is
focused on the development of infrastructure for combining
high-performance computing with scientific research, and
development of new algorithms for such computations.

My
short-term research goal is to improve the Virtual Neutron Facility
according to feedbacks from scientific researchers who use
neutron instruments, and from instrument scientists who
operate, maintain, and optimize neutron instruments,
in order to make VNF more and more powerful and useful
and benefit the neutron community as a whole.

My bigger, longer-term goal is to make use of my experiences and expertise
in building VNF and related computing tools in various fields of
physical science. An immediate extension of my current research
could be to apply these computing tools to some other branches of scattering physics
including X-ray, transmission electron microscopy, and even
Mossbauer diffractometry. 


