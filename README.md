# NOTE:
***It is HIGHLY RECOMMENDED that you use this mod with my [Smart Marine](https://github.com/inkoalawetrust/Smart-Marines/) mod, if you don't, the MVP will fall back to spawning [the default crappy ZDoom marines](https://zdoom.org/wiki/Classes:ScriptedMarine) instead for vehicles that drop soldiers. I am not liable for any frustrating and moronic behavior they (ZDoom marines) exhibit, and DO NOT REPORT ANY BUGS UNLESS THE SMART MARINES ARE ALSO INCLUDED OR LOADED ALONGSIDE YOUR PROJECT !***
# NOTE:
*This is just an overview of the pack*, for actual documentation read the included document and demo map in the releases page.

Any mention of marines from now on will be about my own marine NPCs.

![](https://i.imgur.com/YVk58JK.gif)

[(Renders of the vehicles.)](https://imgur.com/a/KUhbDRZ)

# Military-Vehicles-Pack
A GZDoom mod that contains a pack of military vehicle NPCs and props, for use in mods and maps.

## What is this ?
Exactly what the description says, a GZDoom mod that contains a pack of military vehicles, that can be used as full fledged NPCs and/or decorations for your projects, full documentation for the mod is also included on the [releases](https://github.com/inkoalawetrust/Military-Vehicles-Pack/releases) section. The vehicle sprites and models are all made by me unless otherwise specified.

## Showcase videos
The below videos serve as showcases and overviews of each of the vehicles that are part of the pack.

### Army Car: https://youtu.be/1droRFw7LEo
### Army Truck: https://youtu.be/au_r7aJN9Lw
### Armored Personnel Carrier: https://youtu.be/lbHNoUZze_w

## What can they do ? (Overview)

### In general (Shared by all vehicles)
- Includes a working headlight system, where the vehicles will turn their headlights on and off dynamically if the area around them gets too dark.
- Try to keep their distance away from all enemies, instead of just blindly charging into their opponents' face like NPCs normally do.
- Eventually stop chasing their enemy if it has gone out of sight for too long. Instead of trying to chase them forever like normal NPCs.
- Turret weapons have the ability to calculate their targets' trajectory while shooting, instead of dumb firing at where the target is at the time of shooting.

### The Army Car
![](https://i.imgur.com/92UUuKGm.jpg)
- Includes an (Optional) [Pain](https://www.youtube.com/watch?v=kzG4oEutPbA) [Ray](https://en.wikipedia.org/wiki/Active_Denial_System) that can stun groups of most weak enemies, while the pain ray is charging up, any enemy marines near the target zone will begin running away, like they run from grenades.
- Drops down 3 marines (Except the driver.), that can then attack on behalf of the cars' side, and otherwise act like normal marines.
- Can carry different types of supplies that players on the cars' side can use, using the cars' supplies while it is moving will cause it to stop for a bit, so you don't need to chase it around to get more ammounition/health/armor.
- Includes multiple different prop versions of the car, from different versions of the car when it is destroyed, to a configurable prop of the normal, non-destroyed car.

### The Army Truck
![](https://i.imgur.com/MOu9Xatm.png)
- Has 100 more health than the Army Car, however, it's overall more fragile than the Car, and is especially more vulnerable to the "Explosion" "ExplosiveImpact" and "Grenade" "MarineGrenade" damage tyoes. 
- Has no weapons of its' own, not even a non-lethal one like the Army Car. However, it can deploy up to 14 marines (Or more if you want it to.). This allows it to be much more potentially dangerous than the Army Car (Or several of them.).
- Has the (Optional) ability to ram enemies, causing a ton of melee damage based on the speed at which it hits. The truck only rams enemies once it has no marines left inside. And if it hits any ally, it simply pushes them out of the way, all marines will try to run away from the truck while it's ramming.
- Includes multiple different prop versions of the truck, from different versions of the truck when it is destroyed, to a configurable prop of the normal, non-destroyed truck.

### The APC
![](https://i.imgur.com/bajJ0B1m.jpg)
- Has 1500 health and decent durability against a range of damage types, particularly the "Explosion" "ExplosiveImpact" and "Grenade" "MarineGrenade" damage types.
- Can carry up to 8 marines, the marine deploying is more or less the same as on the Army Truck.
- Is the first vehicle in the pack to actually be armed with a lethal weapon, it has a dual machine gun turret, which more or less acts like a way less squishy and mobile version of marines on machine gun emplacements. And also includes an autocannon, which fires slower, but shoots explosive shells that both do a lot of direct impact damage and explosion damage. The autocannon turret also has a smaller MG attached to it, which fires projectile bullets that are 2-2.5x more powerful per shot than the marines' rifles. Naturally, the small MG is also fairly weak. All the turrets have the ability to rotate around properly instead of snapping in place, and also have the ability to visually change their gun elevation based on the turrets' pitch. All of them can also predict the trajectories of enemies by default, instead of firing at wherever the target was at the time of firing.
- Has the ability to crush corpses that are small enough to fit under it. By default, the APC will in fact intentionally go up to, and crush nearby corpses if it's not pre-occupied or ordered to follow a player or stand still. It can also be set to not crush corpses at all, or to only passively crush them as it drives around.
- Unlike the previous two vehicles, the APC has a chance for its' passengers to survive. Which means that there is a chance for a random amount of its' surviving passengers, to run out of the APC after it has been destroyed. All the survivors will have varying amount of lowered health of course.
- Included multiple prop and destroyed versions of the vehicle. The destroyed props in particular are a lot more configurable than on the last two vehicles.

### The Di-Cokka
![](https://i.imgur.com/6n0kr7Im.png)
- Is not an original vehicle, instead it's from Metal Slug. Being a cartoon tank, it has very different properties from the rest of the vehicles, detailed below.
- Only has 600 health (As much as Mancubus) and very little damage factors. Making it even more fragile than the Army Car overall.
- Is overall a bit dumber than the other vehicles. It doesn't have much unique AI code besides what's already shared between vehicles. This is intentional. It's a cartoon tank.
- The Di-Cokkas’ turret does not use the realistic turret traverse that other vehicles use. Unless User_RealisticTurretTurn is on.
- Fires much slower shell projectiles than any other vehicle. It also does not track its' targets' trajectory to fire by default, unless User_TargetPrediction is on.
- Can sometimes fire a volley of 3 shots instead of 1, which is more in line with the Di-Cokkas' attack in the Metal Slug games.
- Can be recolored with the User_Color user variable, more information available in the written documentation.
- Can actually flinch from pain like a normal monster. Which causes the turret to fly back. Can also flinch from taking over 40 damage, which causes the turret to fly even further back, and the tank to be stunned for a bit. Similar to some of the vehicles in Metal Slug (But not the Di-Cokka itself, which had no real pain animation in MS).
- Produces fire particles and a different movement sound when it's health is low enough.
- Dies by just falling apart like in MS, not exploding like other vehicles. When gibbed, it falls apart, then completely explodes into a shower of debris, again, like it does in the original games.
- Uses as many Metal Slug sprites and sounds as I could find.
