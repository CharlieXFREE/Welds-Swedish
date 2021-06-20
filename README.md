# Welds-Swedish
Welds Swedish / svetsar Svenska

# Steg 1, 
Om du vill göra en svets gör du så här
```lua
local <Namn> = svets
```
# Steg 2, 
Om du vill configurera Svetsen så gör du så här
```lua
Svets:Config(<Svets>,<Kropsdel>,<Hatt>,<X>,<Y>,<Z>)
```
# Steg 3,
Om du vill ta bort en mask från ett object då gör du så här
```lua
 Svets:TaBortMask(<Hatt>)
```
# Steg 4, 
åter-Position och Rotation åter positionera eller rotera ett object igen
```lua
Svets:PosRot(<weld>,<X>,<Y>,<Z>,Rot,<Y.Rot>,<Z.Rot>,<X.Rot>)
```
# Steg 5, 
KnapTryck känna av om spelaren Trycker På en viss Knap på TangentBordet
```lua
Knap.KeyDown:connect(function(knap)
				if knap == <knap> then
				   
				    end
				end)
```
