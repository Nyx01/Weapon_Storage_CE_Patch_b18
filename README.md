# Weapon_Storage_CE_Patch
A simple XML patch for KV's Weapon Storage for RimWorld B18.
When Combat Extended is installed, they added Ammo and Turret catagories under Weapons. This causes pawns to
run around trying to put these items in the storage box, however, it's not configured to do so. This causes the
occasional error in the log, and the pawns to get stuck in a haul loop, trying to carry ammo to the box, but dropping
it next on the floor next to it, which they repeat over and over again. This patch simply removes the potential
for Ammo or Turrets to be stored in the Weapons Storage box, preventing this bug from happening.
