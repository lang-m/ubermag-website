========
Workshop
========

Interactive Workshop to get started

Videos on YouTube => Link

Notebooks can be executed in the Cloud (Binder)

Session 1
=========

In this session, we are going to familiarise ourselves with micromagnetics,
Python, and Jupyter and we are going to spend most of the time looking at
slides. Slides can be found in `slides` directory in the workshop `repository
<https://github.com/ubermag/workshop>`_. After slides, we are going to write our
first Ubermag simulation and have a look at some Python basics.

.. toctree::
    :maxdepth: 1
    :caption: Session 1
    :numbered:

    first-ubermag-simulation
    python-basics
    
We believe we do not need much Python knowledge in order to run ubermag.
However, more you feel confident writing Python, more benefits you can get from
ubermag. There are many resources online you can choose from. We can recommend
the online one by Hans Fangohr:

- https://fangohr.github.io/teaching/python/book.html

Session 2
=========

In the previous session, we introduced some very basic concepts of Ubermag
simulations, had a look at some basic Python syntax, and familiarised ourselves
with Jupyter environment. In session 2, we are going to have a look into more
details of Ubermag simulations, so we can start simulating some real-world
problems. In the first half of the session, we are going to analyse the skeleton
of Ubermag simulation and quickly go through the three main concepts
(magnetisation field, energy equation, and dynamics equation). In each tutorial,
we introduce some data analysis and visualisation concepts, which are then going
to be the main focus of session 3. After the break, we are going to simulate
vortex dynamics, drive domain walls with a spin-polarised current, and have a
look at the exercise.

.. toctree::
    :maxdepth: 1
    :caption: Session 2
    :numbered:
    
    magnetisation-field
    energy-equation
    dynamics-equation
    vortex-dynamics
    spatially-varying-parameters1
    spatially-varying-parameters2
    periodic-boundary-conditions
    driving-dw
    dw-pair-conversion

Session 3
=========

The main topic of this session is going to be data analysis and visualisation.
However, similar to the previous sessions, we are going to go through tutorials,
which are going to introduce a mixture of simulation techniques and
micromagnetic concepts as well.

.. toctree::
    :maxdepth: 1
    :caption: Session 3
    :numbered:
    
    choosing-runner
    multiple-terms
    rkky
    time-dependent-field
    negative-A
    energy-term-computations
    field-operations1
    field-operations2
    file-formats
    line
    table-basics
    table-visualisation
    table-interactive-plot
    region-visualisation
    mesh-visualisation
    mpl-visualisation
    k3d-visualisation
    interactive-plotting
    various-topics

Session 4
=========

Here we look at some new features of Ubermag regarding data analysis as well as
simulation techniques.

.. toctree::
    :maxdepth: 1
    :caption: Session 4
    :numbered:
    
    angle-hls-plot
    hysteresis
    dirname
    fixed-subregions
    parallel
    mindriver-steps
    subfields
    space-time-field
    sine-hysteresis
    integrals
