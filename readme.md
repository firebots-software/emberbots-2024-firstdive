# emberbots-2024-firstdive
Software repository for team 26106 Emberbots - Fremont High School, Sunnyvale CA for the 2024-2025 FTC game "Into The Deep"

## Files currently maintained for competition (/comp_ready)
TeleOp OpMode                   
`2024TeleOp.blk`    
  
Current Auton OpModes (T_ indicates the tiles from the left of the field)     
`2024AutonBasketT2.blk`       
`2024AutonBasketRightT3.blk`       
`2024AutonBasketRightT4.blk`         
      
        
### TeleOp: 2024TeleOp.blk
Full control by a driver and arm operator   
#### Key Features:
* Slowmode for the driver
* Scaled down strafe and rotate function for the arm operator (whichever driver's input is greater will be taken)
* Viperslide presets
* Customized intake/outtake behaviour based on drivers' preference
* Software limits on both the rotator and viperslide
    
     
### Auton: 2024AutonBasketT2.blk, 2024AutonBasketRightT3.blk, 2024AutonBasketRightT4.blk
Autonomous OpModes to score in the high basket
#### Key Features:
* Precise forward and backward movement utilizing encoders
* Precise turning in degrees utilizing the IMU
* Full rotator, viperslide, and wrist movement to successfully score a sample in the high basket
* Reset to prepare for TeleOp
* Auton Abort to outtake and reset if time is low (only implemented in AutonBasketT2 currently)
