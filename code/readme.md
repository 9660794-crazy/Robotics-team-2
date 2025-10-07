this is the place to put the VEXcode.
fieldlength = 0

def when_started1():
    global fieldlength
    drivetrain.set_drive_velocity(85, PERCENT)
    drivetrain.drive_for(FORWARD, 10, INCHES, wait=True)
    drivetrain.set_turn_velocity(30, PERCENT)
    drivetrain.turn_for(RIGHT, 12, DEGREES, wait=True)
    drivetrain.drive_for(FORWARD, 10, INCHES, wait=True)
    drivetrain.stop()

when_started1()
