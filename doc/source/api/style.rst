{{ header }}

.. _api.style:

=====
Style
=====
.. currentmodule:: pandas.io.formats.style

``Styler`` objects are returned by :attr:`pandas.DataFrame.style`.

Styler Constructor
------------------
.. autosummary::
   :toctree: generated/

   Styler
   Styler.from_custom_template

Styler Properties
-----------------
.. autosummary::
   :toctree: generated/

   Styler.env
   Styler.template
   Styler.loader

Style Application
-----------------
.. autosummary::
   :toctree: generated/

   Styler.apply
   Styler.applymap
   Styler.where
   Styler.format
   Styler.set_precision
   Styler.set_table_styles
   Styler.set_table_attributes
   Styler.set_caption
   Styler.set_properties
   Styler.set_uuid
   Styler.clear
   Styler.pipe

Builtin Styles
--------------
.. autosummary::
   :toctree: generated/

   Styler.highlight_max
   Styler.highlight_min
   Styler.highlight_null
   Styler.background_gradient
   Styler.bar

Style Export and Import
-----------------------
.. autosummary::
   :toctree: generated/

   Styler.render
   Styler.export
   Styler.use
   Styler.to_excel
