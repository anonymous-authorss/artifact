Installation
^^^^^^^^^^^^

Install from source
"""""""""""""""""

.. code-block:: bash

   # 1. Create a clean conda environment
   conda create -n causalcompass-env python=3.10 -y
   conda activate causalcompass-env

   # 2. Install causalcompass from this repository
   pip install .

   # 3. Verify installation
   pip show causalcompass
   python -c "import causalcompass; print(dir(causalcompass))"
