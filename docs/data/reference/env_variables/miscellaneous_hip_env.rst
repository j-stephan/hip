The following table lists environment variables that are useful but relate to
different features in HIP.

.. _hip-env-other:
.. list-table::
    :header-rows: 1
    :widths: 35,14,51

    * - **Environment variable**
      - **Default value**
      - **Value**

    * - | ``HIPRTC_COMPILE_OPTIONS_APPEND``
        | Sets compile options needed for ``hiprtc`` compilation.
      - Unset by default.
      - ``--gpu-architecture=gfx906:sramecc+:xnack``, ``-fgpu-rdc``
