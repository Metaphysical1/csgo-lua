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
on_create_move                  userCmd							runs after ClientModeShared::CreateMove
on_frame_stage_notify           number (stage)					runs after CHLClient::FrameStageNotify
on_fire_game_event              gameEvent						runs inside event listener
on_present                      nothing							runs inside directx present hook
on_override_view                viewSetup						runs after ClientModeShared::OverideView
on_script_UI                    nothing							called inside lua settings menu
=============================== =============================== =============================== 

Examples
--------

.. code-block:: lua

   fovOverride = 0
   
   function scriptSettings()
   fovOverride = Gui.slider("fov override", fovOverride, -20,20)
   end
   
   function fovChanger(setup)
   setup.fov = setup.fov+fovOverride
   end
   
   hookFunction(fovChanger,"on_override_view")
   hookFunction(scriptSettings,"on_script_UI")