.. meta::
    :description: HIP environment variables reference
    :keywords: AMD, HIP, environment variables, environment, reference

********************************************************************************
HIP environment variables
********************************************************************************

In this section, the reader can find all the important HIP environment variables
on AMD platform, which are grouped by functionality.

GPU isolation variables
================================================================================

Restricting the access of applications to a subset of GPUs, also known as GPU
isolation, allows users to hide GPU resources from programs. The GPU isolation
environment variables in HIP are collected in the following table.

.. include-table:: data/env_variables_hip.rst
    :table: hip-env-isolation

Profiling variables
================================================================================

The profiling environment variables in HIP are collected in the following table.
For more information, check :doc:`setting the number of CUs page <rocm:how-to/setting-cus>`.

.. include-table:: data/env_variables_hip.rst
    :table: hip-env-prof

Debug variables
================================================================================

The debugging environment variables in HIP are collected in the following table.
For more information, check :doc:`hip:how-to/logging`, :doc:`hip:how-to/debugging`
and :doc:`GPU isolation <rocm:conceptual/gpu-isolation>`.

.. include-table:: data/env_variables_hip.rst
    :table: hip-env-debug

Memory management related variables
================================================================================

The memory management related environment variables in HIP are collected in the
following table. The ``HIP_HOST_COHERENT`` variable linked at the following
pages:

- :ref:`Coherence control <hip:hip-memory-coherence-table>`

- :ref:`Memory allocation flags <hip:memory_allocation_flags>`

.. include-table:: data/env_variables_hip.rst
    :table: hip-env-memory

Other useful variables
================================================================================

The following table lists environment variables that are useful but relate to
different features.

.. include-table:: data/env_variables_hip.rst
    :table: hip-env-other
