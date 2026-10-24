# Puddle jumper

The puddle jumper is a small ship that flies through a stargate with its crew aboard. It seats ten, hovers on a drive you switch on and off, carries six homing drones, and has its own dialing computer, so a crew can dial out, fly through and keep going on the far side.

```infobox
Puddle jumper
Icon: sgcraft:puddle_jumper
ID: sgcraft:puddle_jumper
Image: scenes/puddle-jumper-night.jpg
Type: Entity and item
Stacks: 1
Size: 2.75 wide, 2.5 tall, 7 long
Seats: 10 players
Speed: 11 m/s, 40 m/s with turbo
Weapons: 6 drones
Recipe: [Crafting](#crafting)
Dictionary: [Puddle jumper](entities/puddle-jumper.md)
```

## What it is

A jumper is a vehicle, like a boat or a minecart, that flies. Its hitbox is as wide and tall as a gate's opening, 2.75 by 2.5 blocks, so it fits through a standard gate. It is 7 blocks long, and the whole length collides with blocks. It can't step up onto anything.

It has no fuel and no energy use. Its drive is a switch, on or off. With the drive on, it hangs where it is and flies where you steer it. With the drive off, it falls like anything else.

Anyone can board, fly, pick up or rename a jumper. It has no owner and no access rules, and it has no settings or commands.

## Crafting

```recipe
sgcraft:puddle_jumper
```

## Placing and picking up

- Use the jumper item on a block face. The jumper goes down at the bottom center of the block beside that face, facing the way you face. It only goes down if the whole ship fits, nose to tail. Otherwise you get "There is no room here for a puddle jumper".
- To pick it up, sneak and use it from outside with an empty hand while nobody is aboard. The item goes to your inventory, or drops if your inventory is full. Pick-block gives you the item as well.
- A name tag renames it.
- The item keeps only the jumper's name. A jumper you pick up and put down again has a full set of six drones, its drive off and a blank computer history.

## Boarding and seats

A jumper has ten seats, all for players.

| Seat | Where | What it does |
| --- | --- | --- |
| Helm | Front left | The pilot. Flies the ship and works the dashboard |
| Dialer | Front right | The co-pilot. Works the computer and the weapons |
| Cockpit left and right | Behind the front seats | Passengers |
| Cabin | Six bench seats along the aisle | Passengers |

- Use a jumper from outside to lower or raise its cargo door. Walk up the ramp and you are inside. You can walk around in the hull.
- Standing inside, use the seat you look at to sit in it. Use it while looking at the back of the cabin to work the door. While seated, look at a free seat and use it to move there.
- Riders who get out keep their seat for as long as nobody else takes it. They lose it if they go more than 8 blocks away.
- You can only get up while the jumper stands still. Otherwise you are told to wait until it stops. You stand up beside your seat.
- Anyone still standing inside when it moves is put in a free seat, or out of the back, side or roof if none is free.
- Riders pick up no items or experience, and take no fall damage.
- A rider can look up to 105 degrees either way from the way their seat faces.

## Flying

Only the person in the helm seat flies. Their own game moves the jumper, much like a boat, and everyone else sees it glide.

1. Press the **O** key, or click the POWER button on the dashboard, to switch the drive on. The hull hums.
2. Raise the cargo door if it is down. The jumper won't fly with its door open.
3. Fly.

| Control | What it does |
| --- | --- |
| Forward | Thrust. It speeds up to 11 m/s over about 3 seconds |
| Back | Brakes, then reverses at up to 4 m/s |
| Left and right | Turn, up to 60 degrees a second. The jumper only turns where it has room |
| Jump | Climb at 6 m/s |
| Left Alt | Descend at 6 m/s |
| Sprint with forward | Turbo, up to 40 m/s. It needs the drive pods all the way out |
| Sneak | Stand up from your seat |

With no keys held, it coasts to a stop in about 4 seconds, and it keeps 85 percent of any sideways drift each tick. It banks into turns and tips its nose as it climbs, but those are only for show. There is no height limit.

### Drive pods

The two drive pods fold out when the jumper is in the air, and turbo needs them out. They fold in by themselves within 12 blocks of a connected gate, so the jumper clears the opening. Press **R** to fold them out or in yourself. Your choice stays until you use turbo.

### The cargo door

Press **G**, or click DOOR on the dashboard, to lower or raise the door. The lowered door is a ramp 2.55 blocks long that holds people up even while the jumper hovers. It only moves while the jumper is still or empty. Otherwise you get "Stop the jumper to lower its cargo door". The door and the pods take a second to move.

### Landing and falling

With the drive off, the jumper's sideways speed dies away and it falls, up to 60 m/s, until it lands. Landing turns the weapons off and drops the lock. A jumper that hits a block flying stops at once.

### Terrain

The pilot's game holds the jumper in place until the chunks at and just ahead of it have loaded, keeping its speed, and the HUD says **HOLDING FOR TERRAIN**. Near a connected gate, the server also loads the world on the far side before you get there, so a jump at full speed doesn't arrive in empty space.

## The dashboard

The pilot can click the dashboard's buttons by looking at them. From right to left they are POWER, HEADLIGHTS, PODS, DOOR, WEAPONS and FRIENDLY FIRE. Every one has a key as well, below.

## Keys

All of these are set in **Options, Controls, Puddle Jumper**.

| Key | Name | What it does | Who |
| --- | --- | --- | --- |
| **O** | Jumper Power | Drive on or off | Pilot |
| **H** | Headlights | Headlights on or off, with the drive on | Pilot |
| **R** | Toggle Drive Pods | Pods out or in | Pilot |
| **G** | Cargo Door | Door down or up | Pilot |
| **Left Alt** | Descend | Go down | Pilot |
| **K** | Open Jumper Computer | The dialing computer | Pilot or co-pilot |
| **B** | Arm Drones | Bays out or in. The drive must be on | Weapons |
| **Z** | Lock Next Target | Next target in the lock | Weapons |
| **V** | Launch Drone | Fire at the lock, or straight ahead without one | Weapons |
| **N** | Toggle Friendly Fire | Whether drones may hit things that aren't hostile | Weapons |

The weapons belong to whoever sits in the dialer seat, or to the pilot if nobody does. The other front seat sees the same lock. Everyone else's presses of these keys are ignored.

## Headlights

With the drive on, **H** lights a cone under the nose that reaches 36 blocks, a little over 26 degrees to each side and angled 9 degrees down. The light is drawn on your game only, and no light blocks are placed in the world. The lamps work when the sky is dark, and always in a dimension with fixed time or no sky light. Underwater, the lamps let you see 1.6 times as far.

## The cabin

The cabin is sealed. For anyone inside, the hull keeps out water, rain, snow, fire and lava:

- Riders breathe and see clearly with no water fog, even with the ship underwater.
- Rain and snow stop at the roof.
- Fire and lava do no damage to riders, and fire on them goes out.
- Mobs don't pick riders out as targets, and riders' name tags are hidden.
- Grass and flowers inside the hull aren't drawn.
- Riders' held items aren't shown.

It does not shield riders from explosions or other damage.

## The heads-up display

Riders see a console drawn over the game, in Atlantis blue, in place of the hotbar. Boss bars are hidden while you ride. The camera in third person sits at least 10 blocks back, and the view widens to at least 100 degrees.

- Compass tape. Along the top, 50 degrees either way, with a tick every 5 degrees and a reading such as `045° NE`.
- Left pane, the scanner. The dimension and time of day, the biome, a round map, your coordinates, and the distance to the linked gate (`GATE 340 m`) or `NO GATE`. The map turns so ahead is always up, reaches 72 blocks, and shades the relief 32 blocks up and down. Ground that isn't loaded stays dark. The linked gate shows as a green diamond, pinned to the rim of the map when it is out of range.
- Right pane, the instruments. A speed dial in m/s, a height dial in blocks, the height above ground (`AGL`), the climb rate, **DRIVE ON** or **DRIVE OFF**, and the drones you have left (an infinity sign in creative).
- Lamps. PODS, TURBO, LIGHTS, DOOR, ARMED and FRIEND, each lit while that is so.
- Gate marker. A diamond with its distance on the linked gate while it is on screen.
- Key card. Bottom left, in the front seats, listing the keys that seat can use.
- Pilot only. A flashing `DOOR DOWN, RAISE TO FLY`, `HOLDING FOR TERRAIN`, and a reticle in first person or a chevron over the nose in third.

## Weapons

A jumper carries six drones, and has no way to reload them. They come back only if you pick the jumper up and put it down again.

1. With the drive on, press **B**. The bays slide out in half a second and the jumper is armed. Switching the drive off, or landing, disarms it.
2. The scanner marks what is in front of you. Z picks the next mark.
3. Press **V** to launch a drone. Drones leave from the left and right bays in turn, one every 8 ticks at most.

### Targets

The scanner looks in a cone 25 degrees either way, out to 128 blocks, and only sees what has a clear line of sight. A mark lasts 10 ticks after you lose sight of it.

- Hostile mobs are always marked, in red.
- Players are marked in purple and other living things in blue, but only with friendly fire on.
- Armor stands, invisible things, spectators, you, and anyone sitting in a jumper are never marked.
- With nothing locked, the lock goes to the mark nearest the middle. **Z** picks the next one and holds it until it dies, leaves, or passes 128 blocks. **Z** with nothing marked lets go of the lock.
- The locked target gets corner brackets, its name, `LOCK 64 m`, and a health bar under the compass. If it is off screen, a diamond at the edge of the screen shows which way to turn.

### Drones

A drone flies at 32 m/s. With a lock it leaves sideways and up, then homes in, turning toward its target. With no lock it flies straight ahead. It bursts when it hits a creature or a block, or comes within 1.5 blocks of the place it was aimed at, or after 10 seconds.

The blast has the strength of 2.5, a little under a creeper's 3, and starts no fires. It breaks blocks only where mobs may. It never hurts a jumper or anyone inside one, and with friendly fire off it spares everything that isn't hostile. A drone aims at an Ender Dragon's head.

Creative pilots never run out of drones.

## The computer

Press **K** to open the dialing computer from the dialer seat. The pilot can open it too, if nobody sits in the dialer seat; with someone there, the pilot is told "The computer is worked from the seat beside you". It works like the [dialing computer](blocks/dialing-computer.md) on a desk, with the same gate, slow and fast modes, dialing, abort, iris and alarm controls, and a history of what you dialed. Its screen shows on the dashboard.

- It links to the nearest gate within 512 blocks, in the same dimension, and links again every second as you fly, unless the gate it is linked to is busy.
- It needs the drive on. With the drive off, the screens close and the computer says it is dark.
- Dialing goes through the gate's own rules, so the gate's energy and access rules apply. The jumper brings no power of its own.

## Through a gate

- A jumper goes in nose first or tail first, and comes out of the far gate's front with its speed and its riders. Riders keep their seats and the way they were looking, even to another dimension.
- Everyone aboard needs the right to use both gates. If one rider doesn't have it, nobody goes through and they are told "You aren't allowed to travel through this gate".
- A shut iris at the far end destroys the jumper and kills everyone aboard, and clears their inventories unless the gate keeps them or `keepInventory` is on. Creative players are warned "Destination blocked by iris" instead. A [Tollan phase shift device](items/tollan-phase-shift-device.md) in a rider's hand doesn't help, because it is the jumper that travels.
- A one-way wormhole entered from its receiving end kills the jumper's riders. Creative players are told "You can't travel backwards through a one-way wormhole".
- The kawoosh of an opening wormhole doesn't hurt the jumper, but it does hurt riders in its path.

See [What a shut iris does](iris.md#what-a-shut-iris-does).

## Damage

The jumper is a vehicle and has no hearts. Hits add to a damage count that falls by 1 a tick, and the jumper breaks when the count passes 40. It takes a fifth of the damage a boat would, and it is immune to fire.

Nobody inside it can hurt it. It drops its item when it breaks, and nothing at all when a creative player hits it.

## Sounds

The drive hums while it is on, a little louder and higher with more thrust, and can be heard within 40 blocks. It has its own sounds for powering on and off. The door and the dashboard buttons click.

## See also

- [Puddle jumper in the dictionary](entities/puddle-jumper.md)
- [The dialing computer](blocks/dialing-computer.md)
- [Dialing](dialing.md#the-dialing-computer)
- [Iris](iris.md)
- [Access rights](access.md)
