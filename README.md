<h1 align="center">Bug Report</h1>

#### Please report these fastflags to devforum

### Disables PGS Solver
```json
{ "FFlagSimDefaultPGSSolver": "False" }
```
### No Animations
```json
{ "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1" }
```
### Stick unanchored parts to you
```json
{ "DFIntSolidFloorPercentForceApplication": "-1000", "DFIntNonSolidFloorPercentForceApplication": "-5000" }
```
### Max Raycast Distance
###### Break legs collision from 2 to -inf, kinda break camera on values over 3
###### noclip cam on 3
```json
{ "DFIntRaycastMaxDistance": "3" }
```
### Possible Super Jump
```json
{ "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500" }
```
### It allows you to fall quicker and ignore certain block designs
```json
{ "FFlagHumanoidOnlySetCollisionsOnStateChangeDefaultIsEnabled": "False", "FFlagHumanoidParallelFasterSetCollision": "True" }
```
### Fake Lag
```json
{ "DFIntS2PhysicsSenderRate": "1" }
```
### Invisible
```json
{ "DFIntS2PhysicsSenderRate": "-30" }
```
### Invisible 0,0,0
```json
{ "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10" }
```
### Clientsided Invisible
```json
{ "FIntParallelDynamicPartsFastClusterBatchSize": "1" }
```
### Warp & Physics FPS cap
```json
{ "DFIntMaxMissedWorldStepsRemembered": "1" }
```
```json
{ "DFIntMaxMissedWorldStepsRemembered": "1000" }
```
### Noclip
###### adjust the value so u dont fall through the ground
```json
{ "DFFlagAssemblyExtentsExpansionStudHundredth": "-50" }
```
### Hip Height
###### Very controllable bounce, only works with negative values, 0 allows you to hover
```json
{ "DFIntMaxAltitudePDStickHipHeightPercent": "-200" }
```
### Wallglide
```json
{ "DFIntUnstickForceAttackInTenths": "-4" }
```
### Enables Network Debug Tracker menu
##### Instructions: CTRL+F8
```json
{ "DFFlagDebugEnableInterpolationVisualizer": "True" }
```
