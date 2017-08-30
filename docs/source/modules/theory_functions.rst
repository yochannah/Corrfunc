.. _theory_functions:

Detailed API for Clustering Statistics on Simulations
=======================================================

All of these can be imported from :py:mod:`corrfunc.theory`. See the complete reference here :py:mod:`corrfunc`.

.. currentmodule:: corrfunc.theory

Clustering in 3-D
------------------

* Pair counts for (auto or cross) correlations for :math:`\xi(r)` -- :py:mod:`corrfunc.theory.DD`
* Auto-correlation on periodic, cosmological boxes, :math:`\xi(r)`, -- :py:mod:`corrfunc.theory.xi`

Clustering in 2-D
------------------

* Pair counts (auto or cross) correlations for :math:`\xi(rp, \pi)` -- :py:mod:`corrfunc.theory.DDrppi`
* Projected auto-correlation function, :math:`wp(rp)` --  :py:mod:`corrfunc.theory.wp`

Counts-in-cells
----------------

* Void Probability functions and counts-in-cells stats :math:`pN(r)` -- :py:mod:`corrfunc.theory.vpf`
