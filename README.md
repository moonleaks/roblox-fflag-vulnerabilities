# leaking fflags that have glitches

# P.S dont gatekeep a fflag
I HAVENT TESTED MOST OF THESE IF THEY ARE PATCHED SORRY

# <img src="https://github.com/devstacking/Roblox.Glitching.Community.FFlags.Collective/assets/106433721/fc3f1971-3161-4c27-8e5e-95ae69363b40" width="24"/> Roblox Glitching Community FFlags

### creds; fastvar

 # List Navigation
* **[Physics](https://github.com/devstacking/Roblox.Glitching.Community.FFlags.Collective#physics-changing-flags)**

# Physics Changing FFlags

### 1. FPS Cap
```json
{
	"DFIntTaskSchedulerTargetFps": "9999"
}
```
### 2. Causes some character collision from jumping physics breakdown, making model ragdoll
```json
{
	"DFIntLandedBalanceD": "-2000"
}
```
### 3. All type of wallhops, longjumps, headhitters and probably more stop working
```json
{
	"DFFlagSimHumanoidPhysics": "True"
}
```
### 4. Break legs collision from 2 to -inf, kinda break camera on values over 3
```json
{
	"DFIntRaycastMaxDistance": "0"
}
```
### 5. Kinda breaks movement and some other stuff on higher negative values
```json
{
	"FIntPGSAngularDampingPermilPersecond": "-10000"
}
```
### 6. Default is for the first one is "True". Basically with False, and True. It allows you to fall quicker and ignore certain block designs. For example if you're playing phantom forces and normally if you go up a slanted hill that goes upward it makes you slower. But, this makes you pretty much have no slowdowns.
```json
{
	"FFlagHumanoidOnlySetCollisionsOnStateChangeDefaultIsEnabled": "False",
	"FFlagHumanoidParallelFasterSetCollision": "True"
}
```
### 7. Gear DeSync
```json
{
	"DFIntDataSenderRate": "-1"
}
```
### 8. Another noclip fflag but acts differently
```json
{
	"DFFlagAssemblyExtentsExpansionStudHundredth": "150"
}
```
### 9. Freezes character in any state, can cause crashes, basically stacks input data
```json
{
	"FFlagSimIslandizerManager": "False"
}
```
### 10 & 14
### Spin when moving
```json
{
	"DFIntRunningBaseOrientationP": "-14"
}
```
### Spin when falling
```json
{
	"DFIntRunningBaseOrientationP": "-14"
}
```
### 11. Makes character upside down
```json
{
	"DFIntFreeFallBalanceP": "-9999"
}
```
### 12. Makes character ragdoll forever
```json
{
	"DFIntGettingUpBalanceP": "0"
}
```
### 13. Fake Lag
```json
{
	"DFIntS2PhysicsSenderRate": "1"
}
```
### 15. Noclip FFlags Combo
###### no i didnt skip 14
```json
{
	"FIntPGSPenetrationMarginMax": "2147483647",
	"FIntPGSPenetrationMarginMin": "2147483647"
}
```
### 16. Allows you to boounce when flicking
###### no i didnt skip 14
```json
{
	"DFIntNewRunningBaseAltitudeP": "49534"
}
```
### 17. Ragdoll Loop 
###### only when you are already in a ragdoll state
```json
{
	"DFIntGettingUpBalanceD": "-110000"
}
```
### 18. Bounces character constantly at 0 
###### Jump to randomly bounce yourself high
```json
{
	"DFIntNewRunningBaseAltitudeD": "0"
}
```
### 19. Very limited speed fflag that works only in a few games
###### one of them being Phantom Forces, and it makes you only slightly faster
```json
{
	"DFIntDebugSimPhysicsSteppingMethodOverride": "10000000"
}
```
### 20. Makes it so your gravity is reduced by a factor of Int value you put in when on the ground, weird trigger + very sensitive (2000 makes you fling like 100 studs up everytime u touch the floor) 1500 makes you "hop" very quickly on the ground, if u hold jump sometimes you are able to jump with the gravity reduction meaning a super jump
```json
{
	"DFIntNewRunningBaseGravityReductionFactorHundredth": "1000"
}
```
### 21. Hip Height
###### Very controllable bounce, only works with negative values, 0 allows you to hover
```json
{
	"DFIntMaxAltitudePDStickHipHeightPercent": "-200"
}
```
### 22. Head Collisions R15
```json
{
	"FFlagMeshPartHeadsDefaultIsEnabled": "False"
}
```
### 23. Physics FPS
```json
{
	"FFlagDebugSimIntegrationStabilityTesting": "True"
}
```
### Noclip <sup>literally</sup>
```json
{
	"DFIntSHCellMinSizeAsBitShift": "4"
}
```
### Wallglide
```json
{
	"DFFlagUnstickForceAttackInTenths": "-4"
}
```
