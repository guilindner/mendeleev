===================
mendeleev Changelog
===================

Latest version
==============


Features added
--------------

* Added calculation of Martynov and Batsanov scale of electronegativity in 
  ``en_martynov_batsanov`` method in the ``Element`` class

Bugs fixed
----------


v0.2.4 (05-02-2016)
===================

Features added
--------------

* Extended and corrected the documentation and Jupyter notebook tutorials on
  basic usage electronegativities, plotting and tables

Bugs fixed
----------

* Corrected ``raise`` to ``return`` when calling ``en_sanderson`` from
  ``electronegativity``

* Fixed and tested the formula for calculating the Li and Xue scale of
  electronegativity in ``en_lie-xue``

v0.2.3 (27-01-2016)
===================

Features added
--------------

* Added new vdW radii: ``vdw_radius_batsanov``, ``vdw_radius_bondi``,
  ``vdw_radius_dreiding``, ``vdw_radius_mm3``, ``vdw_radius_rt``,
  ``vdw_radius_truhlar``, ``vdw_radius_uff``

* Added an option to plot the long (wide) version of the periodic table in
  ``periodic_plot``

Bugs fixed
----------

* Typos in the docstrings

v0.2.2 (29-11-2015)
===================

Features added
--------------

* Added new covalent radii: ``covalent_radius_bragg``,
  ``covalent_radius_slater``

* Added the ``c6`` dispersion coefficients

* Added ``gas_basicity``, ``proton_affinity`` and ``heat_of_formation``

* Added ``periodic_plot`` function for producing ``Bokeh`` based plots of the
  periodic table

* Added ``jmol_color`` and ``cpk_color`` with different coloring schemes for
  atoms

Bug fixes
---------

* Changed the series of elements 113, 114, 115, 116 to poor metals

v0.2.1 (26-10-2015)
===================

Features added
--------------

* Extended the list of options for calculating Mulliken electronegativities in
  ``en_mulliken``

* Added ``electrons_per_shell`` method

* Added a function to calculate linear interpolation of radii required for
  calculation of Sandersons electronegativity

* Added hybrid attributes ``electrons``, ``protons``, ``neutrons`` and
  ``mass_number``

Bug fixes
---------

* Changed the type of the ``melting_point`` from ``str`` to ``float``

v0.2.0 (22-10-2015)
===================

Features added
--------------

* Instead of ``covalent_radius`` added ``covalent_radius_2008`` and
  ``covalent_radius_2009``

* Instead of ``electronegativity`` added ``en_pauling`` and ``en_mulliken``

* Added a method for getting ionic radii

* Improved the method for calculating the nuclear screening constants

* Added ``ElectronicConfiguration`` class initialized as ``Element`` attribute

* Added nuclear screening constants from Clementi and Raimondi

* Added a method to calculate the absolute softness, absolute hardness and
  absolute electronegativity

* Added ``get_table`` method to retrieve the tables as ``pandas``
  ``DataFrames``

Bug fixes
---------

* Added missing electronic configurations

* Converted ionic radii from Angstrom to pico meters

v0.1.0 (11-07-2015)
===================

First tagged version with the initial structure of the package and first
version of the database and the python interface