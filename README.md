# These files require parts/models in the place in order to function

The hierarchy for the Artillery piece is within the Workspace
#### This is the order of hierarchy:
Workspace -> AT-TE -> AT-TE Cannon -> Seat, Barrel, Base
Barrel includes a firepoint for the artillery shell
Barrel and Base both include HingePoints for movement


#### All scripts require Remote events to function
This is the hierarchy:
Replicated Storage -> Artillery_Remotes -> ClaimArtillery, FireArtillery, OperatorStatus, ReturnArtillery, StrikeResponse, UpdateStrikeQueue

#### There is also a strike designator tool
This is used to send in requests to the Artillery operators, using a coordinate system.
The tool is within the StarterPack folder, and has the StrikeRequest script

Within the ServerScriptStorage folder, there is also the Artillery_Server script, and the StrikeSystem script

