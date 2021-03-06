Manual Hbox Example
===============================================================================

:download:`manual_hbox <../../../examples/layout/advanced/manual_hbox.enaml>`

::

    An example which demonstrates the manual specification of an `hbox`.
    
    This example demonstrates how one would manually define the constraints
    for an `hbox` style layout. In fact, the `hbox` layout helper generates
    the primitive constraints in a fashion very similar to this example.
    The intent of this example is to demonstrate that all of the layout
    helper functions can be distilled down to a list of primitive
    constraints.

::

 $ enaml-run manual_hbox

.. image:: images/ex_manual_hbox.png

.. literalinclude:: ../../../examples/layout/advanced/manual_hbox.enaml
    :language: enaml

