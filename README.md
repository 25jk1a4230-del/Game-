# Village Royale – Phase 1/2 Unity scaffold
Unity 2022 LTS+, Android target, 3D (URP recommended).
Implemented rules: 200 HP, fixed 10 dmg/hit, +50 medikit (cap 200, cancels on move/shoot/damage),
unlimited reserve ammo, zombie instant death, knockdown for Duo/Squad, shrinking safe zone, 15-slot roster.
Setup: copy Assets/ into a Unity project; bake a NavMesh; tag player "Player"; add Health+PlayerInventory+Weapon;
create WeaponData assets (6 types); add ZombieSpawner with spawn points in the training scene.
Next per your spec: controller + camera, mobile HUD, lobby, AI opponents, accounts, multiplayer.
