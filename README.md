# gms_scheduler_fix
Thread scheduler resolution fix for GM:Studio and GM8.1

This hack works by providing a fake DBGHELP.DLL stub that sets the scheduler resolution to 1ms, providing a smooth framerate across all studio and 8.1 games. The games are unmodified and no hook/patching is done.
