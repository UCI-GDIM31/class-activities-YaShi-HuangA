# in-class-activities
## Devlogs
### W1
Write your W1 activity Devlog here.

### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.

### W3
bool DidPlayerHitBeat(float keyPressTime, float beatTime, float hitWindow) 
{
    return Math.Abs(keyPressTime - beatTime) <= hitWindow;
}


## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 

### W4
table #4 
line 5: SerializeField make this variable visible and it is private. Float is a number like 1.0. _moveSpeed is how fast the cat moves and it is 1.0f
Line 22: This fLoat variable caLled transLation and it is a player's input on Vertical axis, This multipLies cat's speed multipLies Time_deLtatime makes this frame by frame at the same speed
Line 25: The transforn of the game object and translate(x, y, 2) make it moves forward and backward.