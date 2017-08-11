********
Examples
********

Nengo creates these models using the principles of the
`Neural Engineering Framework <http://compneuro.uwaterloo.ca/research/nef.html>`_.
The first set of examples explains these three principles:
*representation*, *transformation*, and *dynamics*.

For a summary of these principles, see the following example:

.. toctree::

   examples/advanced/nef_summary

The following examples give a more detailed presentation:

Principle 1: Representation
===========================

.. toctree::

   examples/basic/single_neuron
   examples/basic/two_neurons
   examples/basic/many_neurons
   examples/basic/2d_representation
   examples/basic/combining
   examples/basic/addition

Principle 2: Transformation
===========================

.. toctree::

   examples/basic/communication_channel
   examples/basic/squaring
   examples/basic/multiplication

Principle 3: Dynamics
=====================

.. toctree::

   examples/dynamics/integrator
   examples/dynamics/controlled_integrator
   examples/dynamics/controlled_integrator2
   examples/dynamics/oscillator
   examples/dynamics/controlled_oscillator
   examples/dynamics/lorenz_attractor

Putting these three principles together allows us to scale
these examples up to larger networks that do more complex functions.
Below are some of these complex functions,
as well as other examples that we hope will be helpful
as reference when building your own Nengo models.

Nodes
=====

.. toctree::

   examples/usage/delay_node

Processes
=========

.. toctree::

   examples/advanced/processes

Ensembles
=========

.. toctree::

   examples/usage/tuning_curves
   examples/advanced/izhikevich

Connections
===========

.. toctree::

   examples/advanced/inhibitory_gating
   examples/advanced/functions_and_tuning_curves

Learning
========

.. toctree::

   examples/learning/learn_communication_channel
   examples/learning/learn_square
   examples/learning/learn_product
   examples/learning/learn_unsupervised
   examples/learning/learn_associations

Networks
========

.. toctree::

   examples/networks/ensemble_array
   examples/advanced/matrix_multiplication
   examples/networks/basal_ganglia
   examples/networks/integrator_network

Semantic Pointer Architecture
=============================

.. toctree::

   examples/spa/associative_memory
   examples/spa/convolution
   examples/spa/question
   examples/spa/question_control
   examples/spa/question_memory
   examples/spa/spa_parser
   examples/spa/spa_sequence
   examples/spa/spa_sequence_routed

Extending Nengo
===============

.. toctree::

   examples/usage/rectified_linear
