# Ramdroids 2025-26

FTC robot code for the Ramdroids, 2025-26 season.

## Our code

Everything we write lives in [`TeamCode/src/main/java/org/firstinspires/ftc/teamcode`](TeamCode/src/main/java/org/firstinspires/ftc/teamcode).

| File | Driver Station name | What it does |
|---|---|---|
| `AutoBlue.java` | Auto: Forward → SpinUp → Shoot → Left | Autonomous for the blue side |
| `AutoRed.java` | Auto: Forward → SpinUp → Shoot → Right | Autonomous for the red side |
| `TeleOpCode.java` | TeleOp: Mecanum + Shooter + Intake Button Control | Driver-controlled period |
| `mechanisms/AprilTagWebcam.java` | — | AprilTag camera helper (not used by any OpMode yet) |

## Robot configuration

These names must match the robot configuration on the Driver Station:

| Name | Type | Used for |
|---|---|---|
| `front_left_drive` | DC motor | Mecanum drive |
| `front_right_drive` | DC motor | Mecanum drive |
| `back_left_drive` | DC motor | Mecanum drive |
| `back_right_drive` | DC motor | Mecanum drive |
| `intake` | DC motor | Intake |
| `intake2` | DC motor | Intake |
| `shooter1` | DC motor | Shooter |
| `shooter2` | DC motor | Shooter |
| `Webcam 1` | Webcam | AprilTags (only if `AprilTagWebcam` is used) |

## Building

Open this folder in Android Studio, let Gradle sync, then plug in the Robot Controller and press Run.

This project is built on the official [FTC SDK](https://github.com/FIRST-Tech-Challenge/FtcRobotController); see there for SDK documentation and release notes.
