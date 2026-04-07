# Package Index

Generated at: 2026-04-07T05:13:20.607746+00:00

## BasicComponents

### Math::EKF
<a id="mathekf"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/math/EKF](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/math/EKF)
- Dependencies:
  - [Math::LinearAlgebra](#mathlinearalgebra)
- Reverse dependencies:
  - [ChassisLocalization::EKF](#chassislocalizationekf)

### Math::Geometry
<a id="mathgeometry"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/math/Geometry](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/math/Geometry)
- Dependencies:
  - [Math::LinearAlgebra](#mathlinearalgebra)
- Reverse dependencies:
  - [SensorGyro::JY901S](#sensorgyrojy901s)

### Math::LinearAlgebra
<a id="mathlinearalgebra"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/math/LinearAlgebra](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/math/LinearAlgebra)
- Dependencies: none
- Reverse dependencies:
  - [Math::EKF](#mathekf)
  - [Math::Geometry](#mathgeometry)

### bsp::CANDriver
<a id="bspcandriver"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/bsp/can_driver](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/bsp/can_driver)
- Dependencies:
  - stm32cubemx (external)
  - [libs::RingBuffer](#libsringbuffer)
  - [utils](#utils)
- Reverse dependencies:
  - [MotorDrivers::DJI](#motordriversdji)
  - [MotorDrivers::DM](#motordriversdm)
  - [MotorDrivers::VESC](#motordriversvesc)

### bsp::GPIO_Driver
<a id="bspgpio_driver"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/bsp/gpio_driver](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/bsp/gpio_driver)
- Dependencies:
  - stm32cubemx (external)
- Reverse dependencies:
  - [Chassis::Steering4](#chassissteering4)

### libs::CRC
<a id="libscrc"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/utils/crc](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/utils/crc)
- Dependencies: none
- Reverse dependencies: none

### libs::Concurrency
<a id="libsconcurrency"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/concurrency](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/concurrency)
- Dependencies: none
- Reverse dependencies:
  - [ChassisLocalization::EKF](#chassislocalizationekf)

### libs::Deque
<a id="libsdeque"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/utils/deque](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/utils/deque)
- Dependencies: none
- Reverse dependencies:
  - [ChassisLocalization::EKF](#chassislocalizationekf)

### libs::FixedMap
<a id="libsfixedmap"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/utils/fixed_map](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/utils/fixed_map)
- Dependencies: none
- Reverse dependencies:
  - [MotorDrivers::DM](#motordriversdm)
  - [MotorDrivers::VESC](#motordriversvesc)

### libs::MIT_PD
<a id="libsmit_pd"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/control/mit_pd](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/control/mit_pd)
- Dependencies: none
- Reverse dependencies:
  - [Chassis::Core](#chassiscore)

### libs::PIDMotor
<a id="libspidmotor"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/control/pid_motor](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/control/pid_motor)
- Dependencies: none
- Reverse dependencies:
  - [MotorDrivers::Controller](#motordriverscontroller)

### libs::PID_PD
<a id="libspid_pd"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/control/pid_pd](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/control/pid_pd)
- Dependencies: none
- Reverse dependencies:
  - [Trajectory::MotorTrajectory](#trajectorymotortrajectory)

### libs::RingBuffer
<a id="libsringbuffer"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/utils/ring_buffer](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/utils/ring_buffer)
- Dependencies: none
- Reverse dependencies:
  - [Chassis::ControllerSlave](#chassiscontrollerslave)
  - [bsp::CANDriver](#bspcandriver)

### libs::printf
<a id="libsprintf"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/utils/printf](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/utils/printf)
- Dependencies: none
- Reverse dependencies: none

### protocol::UartRxSync
<a id="protocoluartrxsync"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/protocol/UartRxSync](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/protocol/UartRxSync)
- Dependencies:
  - stm32cubemx (external)
  - [services::Watchdog](#serviceswatchdog)
- Reverse dependencies:
  - [SensorGyro::HWT101CT](#sensorgyrohwt101ct)
  - [SensorGyro::JY901S](#sensorgyrojy901s)
  - [SensorLaser::DT35](#sensorlaserdt35)
  - [SensorLaser::STP23L](#sensorlaserstp23l)
  - [SensorOPS::ActionOPS](#sensoropsactionops)

### services::Watchdog
<a id="serviceswatchdog"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/services/watchdog](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/services/watchdog)
- Dependencies: none
- Reverse dependencies:
  - [MotorDrivers::DJI](#motordriversdji)
  - [MotorDrivers::DM](#motordriversdm)
  - [MotorDrivers::VESC](#motordriversvesc)
  - [protocol::UartRxSync](#protocoluartrxsync)

### traits
<a id="traits"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/libs/traits](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/libs/traits)
- Dependencies: none
- Reverse dependencies: none

### utils
<a id="utils"></a>

- Version: v0.1.0
- Path: [Modules/BasicComponents/utils](https://github.com/your-github-org/BasicComponents/tree/main/Modules/BasicComponents/utils)
- Dependencies:
  - stm32cubemx (external)
- Reverse dependencies:
  - [SensorGyro::HWT101CT](#sensorgyrohwt101ct)
  - [SensorGyro::JY901S](#sensorgyrojy901s)
  - [bsp::CANDriver](#bspcandriver)

## ChassisController

### Chassis::ControllerMaster
<a id="chassiscontrollermaster"></a>

- Version: v0.1.0
- Path: [Modules/ChassisController/Controller/Master](https://github.com/your-github-org/ChassisController/tree/main/Modules/ChassisController/Controller/Master)
- Dependencies:
  - [Chassis::Core](#chassiscore)
  - [VelocityProfile::SCurve](#velocityprofilescurve)
- Reverse dependencies: none

### Chassis::ControllerSlave
<a id="chassiscontrollerslave"></a>

- Version: v0.1.0
- Path: [Modules/ChassisController/Controller/Slave](https://github.com/your-github-org/ChassisController/tree/main/Modules/ChassisController/Controller/Slave)
- Dependencies:
  - [Chassis::Core](#chassiscore)
  - [libs::RingBuffer](#libsringbuffer)
- Reverse dependencies: none

### Chassis::Core
<a id="chassiscore"></a>

- Version: v0.1.0
- Path: [Modules/ChassisController/Core](https://github.com/your-github-org/ChassisController/tree/main/Modules/ChassisController/Core)
- Dependencies:
  - FreeRTOS (external)
  - [libs::MIT_PD](#libsmit_pd)
  - [MotorDrivers::Controller](#motordriverscontroller)
- Reverse dependencies:
  - [Chassis::ControllerMaster](#chassiscontrollermaster)
  - [Chassis::ControllerSlave](#chassiscontrollerslave)
  - [Chassis::Mecanum4](#chassismecanum4)
  - [Chassis::Omni4](#chassisomni4)
  - [Chassis::Steering4](#chassissteering4)
  - [ChassisLocalization::EKF](#chassislocalizationekf)
  - [ChassisLocalization::JustEncoder](#chassislocalizationjustencoder)

### Chassis::Mecanum4
<a id="chassismecanum4"></a>

- Version: v0.1.0
- Path: [Modules/ChassisController/Chassis/Mecanum4](https://github.com/your-github-org/ChassisController/tree/main/Modules/ChassisController/Chassis/Mecanum4)
- Dependencies:
  - [Chassis::Core](#chassiscore)
  - FreeRTOS (external)
- Reverse dependencies: none

### Chassis::Omni4
<a id="chassisomni4"></a>

- Version: v0.1.0
- Path: [Modules/ChassisController/Chassis/Omni4](https://github.com/your-github-org/ChassisController/tree/main/Modules/ChassisController/Chassis/Omni4)
- Dependencies:
  - [Chassis::Core](#chassiscore)
  - FreeRTOS (external)
- Reverse dependencies: none

### Chassis::Steering4
<a id="chassissteering4"></a>

- Version: v0.1.0
- Path: [Modules/ChassisController/Chassis/Steering4](https://github.com/your-github-org/ChassisController/tree/main/Modules/ChassisController/Chassis/Steering4)
- Dependencies:
  - [Chassis::Core](#chassiscore)
  - FreeRTOS (external)
  - [bsp::GPIO_Driver](#bspgpio_driver)
- Reverse dependencies: none

### ChassisLocalization::EKF
<a id="chassislocalizationekf"></a>

- Version: v0.1.0
- Path: [Modules/ChassisController/Localization/EKF](https://github.com/your-github-org/ChassisController/tree/main/Modules/ChassisController/Localization/EKF)
- Dependencies:
  - [Chassis::Core](#chassiscore)
  - [SensorGyro::HWT101CT](#sensorgyrohwt101ct)
  - [Math::EKF](#mathekf)
  - [libs::Deque](#libsdeque)
  - [libs::Concurrency](#libsconcurrency)
- Reverse dependencies: none

### ChassisLocalization::JustEncoder
<a id="chassislocalizationjustencoder"></a>

- Version: v0.1.0
- Path: [Modules/ChassisController/Localization/JustEncoder](https://github.com/your-github-org/ChassisController/tree/main/Modules/ChassisController/Localization/JustEncoder)
- Dependencies:
  - [Chassis::Core](#chassiscore)
- Reverse dependencies: none

## MotorDrivers

### MotorDrivers::Controller
<a id="motordriverscontroller"></a>

- Version: v0.1.0
- Path: [Modules/MotorDrivers/controllers](https://github.com/your-github-org/MotorDrivers/tree/main/Modules/MotorDrivers/controllers)
- Dependencies:
  - [MotorDrivers::Core](#motordriverscore)
  - [libs::PIDMotor](#libspidmotor)
- Reverse dependencies:
  - [Chassis::Core](#chassiscore)
  - [Trajectory::MotorTrajectory](#trajectorymotortrajectory)

### MotorDrivers::Core
<a id="motordriverscore"></a>

- Version: v0.1.0
- Path: [Modules/MotorDrivers/core](https://github.com/your-github-org/MotorDrivers/tree/main/Modules/MotorDrivers/core)
- Dependencies: none
- Reverse dependencies:
  - [MotorDrivers::Controller](#motordriverscontroller)
  - [MotorDrivers::DJI](#motordriversdji)
  - [MotorDrivers::DM](#motordriversdm)
  - [MotorDrivers::VESC](#motordriversvesc)

### MotorDrivers::DJI
<a id="motordriversdji"></a>

- Version: v0.1.0
- Path: [Modules/MotorDrivers/motors/DJI](https://github.com/your-github-org/MotorDrivers/tree/main/Modules/MotorDrivers/motors/DJI)
- Dependencies:
  - [MotorDrivers::Core](#motordriverscore)
  - [bsp::CANDriver](#bspcandriver)
  - [services::Watchdog](#serviceswatchdog)
- Reverse dependencies: none

### MotorDrivers::DM
<a id="motordriversdm"></a>

- Version: v0.1.0
- Path: [Modules/MotorDrivers/motors/DM](https://github.com/your-github-org/MotorDrivers/tree/main/Modules/MotorDrivers/motors/DM)
- Dependencies:
  - [MotorDrivers::Core](#motordriverscore)
  - [bsp::CANDriver](#bspcandriver)
  - [services::Watchdog](#serviceswatchdog)
  - [libs::FixedMap](#libsfixedmap)
- Reverse dependencies: none

### MotorDrivers::VESC
<a id="motordriversvesc"></a>

- Version: v0.1.0
- Path: [Modules/MotorDrivers/motors/VESC](https://github.com/your-github-org/MotorDrivers/tree/main/Modules/MotorDrivers/motors/VESC)
- Dependencies:
  - [MotorDrivers::Core](#motordriverscore)
  - [bsp::CANDriver](#bspcandriver)
  - [services::Watchdog](#serviceswatchdog)
  - [libs::FixedMap](#libsfixedmap)
- Reverse dependencies: none

## Sensors

### SensorGyro::HWT101CT
<a id="sensorgyrohwt101ct"></a>

- Version: v0.1.0
- Path: [Modules/Sensors/gyro/HWT101CT](https://github.com/your-github-org/Sensors/tree/main/Modules/Sensors/gyro/HWT101CT)
- Dependencies:
  - [protocol::UartRxSync](#protocoluartrxsync)
  - [utils](#utils)
- Reverse dependencies:
  - [ChassisLocalization::EKF](#chassislocalizationekf)

### SensorGyro::JY901S
<a id="sensorgyrojy901s"></a>

- Version: v0.1.0
- Path: [Modules/Sensors/gyro/JY901S](https://github.com/your-github-org/Sensors/tree/main/Modules/Sensors/gyro/JY901S)
- Dependencies:
  - FreeRTOS (external)
  - [Math::Geometry](#mathgeometry)
  - [protocol::UartRxSync](#protocoluartrxsync)
  - [utils](#utils)
- Reverse dependencies: none

### SensorLaser::DT35
<a id="sensorlaserdt35"></a>

- Version: v0.1.0
- Path: [Modules/Sensors/laser/dt35](https://github.com/your-github-org/Sensors/tree/main/Modules/Sensors/laser/dt35)
- Dependencies:
  - [protocol::UartRxSync](#protocoluartrxsync)
- Reverse dependencies: none

### SensorLaser::STP23L
<a id="sensorlaserstp23l"></a>

- Version: v0.1.0
- Path: [Modules/Sensors/laser/stp23l](https://github.com/your-github-org/Sensors/tree/main/Modules/Sensors/laser/stp23l)
- Dependencies:
  - [protocol::UartRxSync](#protocoluartrxsync)
- Reverse dependencies: none

### SensorOPS::ActionOPS
<a id="sensoropsactionops"></a>

- Version: v0.1.0
- Path: [Modules/Sensors/ops/ActionOPS](https://github.com/your-github-org/Sensors/tree/main/Modules/Sensors/ops/ActionOPS)
- Dependencies:
  - [protocol::UartRxSync](#protocoluartrxsync)
  - FreeRTOS (external)
- Reverse dependencies: none

## TrajectoryControl

### Trajectory::MotorTrajectory
<a id="trajectorymotortrajectory"></a>

- Version: v0.1.0
- Path: [Modules/TrajectoryControl/MotorTrajectory](https://github.com/your-github-org/TrajectoryControl/tree/main/Modules/TrajectoryControl/MotorTrajectory)
- Dependencies:
  - [VelocityProfile::SCurve](#velocityprofilescurve)
  - [MotorDrivers::Controller](#motordriverscontroller)
  - [libs::PID_PD](#libspid_pd)
- Reverse dependencies: none

## VelocityProfile

### VelocityProfile::Core
<a id="velocityprofilecore"></a>

- Version: v0.1.0
- Path: [Modules/VelocityProfile/Core](https://github.com/your-github-org/VelocityProfile/tree/main/Modules/VelocityProfile/Core)
- Dependencies: none
- Reverse dependencies:
  - [VelocityProfile::SCurve](#velocityprofilescurve)

### VelocityProfile::SCurve
<a id="velocityprofilescurve"></a>

- Version: v0.1.0
- Path: [Modules/VelocityProfile/SCurve](https://github.com/your-github-org/VelocityProfile/tree/main/Modules/VelocityProfile/SCurve)
- Dependencies:
  - [VelocityProfile::Core](#velocityprofilecore)
- Reverse dependencies:
  - [Chassis::ControllerMaster](#chassiscontrollermaster)
  - [Trajectory::MotorTrajectory](#trajectorymotortrajectory)
