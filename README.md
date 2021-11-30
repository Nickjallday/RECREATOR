Xvico X3s Conversion into a PET bottle Stripper/filament maker.

Used a modifed version of Marlin configured for the Xvico MKS Robin Nano Clone.



current configuration_adv.h reflects dual motor mini spool configuration.

// Default Speed when extruding via Recreator 3D LCD screen.
#define DEFAULT_MINIMUMFEEDRATE       5.0     // (mm/s) Minimum feedrate. Set with M205 S.

// Recreator 3D MK3Lite and Pro can both run with E_DUAL_STEPPERS. 
// Ensure 2nd E Motor Driver is not installed in the Lite Configuration.
// Or comment out the following line to leave driver installed.
#define E_DUAL_STEPPER_DRIVERS



current configuration.h reflects dual motor mini spool configuration.
 
//Recreator 3D Big spool diameter of 51 mm and 200-step/16-microstep motor works out to 199.7239 steps/mm
// Recreator 3D Mini spool appox E137.5
#define DEFAULT_AXIS_STEPS_PER_UNIT   { 80, 80, 400, 137.5 }
