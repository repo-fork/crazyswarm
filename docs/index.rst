.. Crazyswarm documentation master file, created by
   sphinx-quickstart on Tue Apr 18 20:00:33 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Crazyswarm's documentation!
======================================

The Crazyswarm projects allows to fly a swarm of nano quadcopters (Bitcraze Crazyflie 2.0)
in tight, synchronized formations.
A motion capture system is required (VICON, OptiTrack, PhaseSpace are supported). We successfully flew 49
Crazyflies using three Crazyradios. An example video for what you can do is shown below:

.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/D0CrjoYDt9w" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>



Our contributed code is licensed under the permissive MIT license, however some of the parts (such as the firmware) are licensed under their respective license. If you use our work in academic research, please cite our paper:

.. code-block:: none

    @inproceedings{crazyswarm,
      Author = {James A. Preiss and Wolfgang H\"onig and Gaurav S. Sukhatme and Nora Ayanian},
      Booktitle = {Proc. IEEE International Conference on Robotics and Automation},
      Title = {Crazyswarm: A Large Nano-Quadcopter Swarm},
      Year = {2017}
    }

Contents:

.. toctree::
   gettingstarted
   installation
   usage
   hardware
   :maxdepth: 2



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

