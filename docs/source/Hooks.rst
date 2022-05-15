Hooks
=====

To hook a function, use ``hookFunction`` function, example:


.. code-block:: lua

   function myFunction(cmd)

   end

   hookFunction(myFunction,"on_create_move")


Hooks destinations
------------------

=============================== =============================== =============================== 
Function                        Arguments                       Description
=============================== =============================== =============================== 
on_create_move                  userCmd
on_frame_stage_notify           number (stage)
on_fire_game_event              gameEvent
on_present                      nothing
on_override_view                viewSetup
on_script_UI                    nothing
=============================== =============================== =============================== 

Examples
--------
