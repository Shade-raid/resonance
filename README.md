RESONANCE is a brutal, single-file text roguelike built in vanilla ES6. It combines the acoustic stealth of Amnesia, the permanent limb-severing combat of Fear & Hunger, and the Action Point/V.A.T.S. targeting of classic Fallout, all wrapped in an authentic, pure-black 80s/90s CRT aesthetic.

Created for Torture Jam, the game focuses on psychological and physical helplessness. You are trapped 4,200 meters below the Siberian permafrost in a facility vibrating at 5.82 Hz. The enemies are blind; they hunt you by sound. Every step you take could be your last.

Core Mechanics

Acoustic Stealth Engine: Sound propagates dynamically via Dijkstra flood-fill. Kicking a door creates a 65dB echo that draws blind enemies from across the map. Walk softly, or don't walk at all.
Fallout-style AP Combat: Engage in turn-based melee using Action Points. Target specific body parts to blind, cripple, or sever the limbs of hostiles. Cripple a Chorus's jaw so it can't bite you.
Fear & Hunger Anatomy: There is no global health bar. Your body is divided into 6 limbs. Fractured legs halve your speed and make you noisy. Amputated arms force you to drop your weapon. Bleed out quietly or die screaming.
The Cognitive Split: The "Crisis Engine" forces you to choose between Heart (Instinct) or Brain (Logic).
Extreme Heart mutates the UI into panicked, misspelled ALL-CAPS screams, granting speed but ruining your accuracy.
Extreme Brain coldly rewrites "blood" to "circulatory fluid" in your logs, granting precision but treating your own limbs as disposable machinery.
Torture Mechanics: Step on rusted Surgical Traps and be forced to choose which limb the machine amputates. A hidden Pain stat causes the screen to physically tremble and your logs to degrade into "PLEASE STOP".
Weapon Throwing: Desperate? Hurl your only weapon at an enemy for massive damage, then scramble to pick it up off the bloody floor before they recover.

Controls

WASD / Arrows: Move (Turn-based)
SPACE: Strike (Opens AP Combat) / Confirm
E: Interact (Terminals, Relays, Elevators, Pickups)
K: Kick Door (Loud)
F: Toggle Lantern
1-5: Use Inventory Items (Medkits, Tapes, Adrenaline, Bandages)
Q / U: Drop Lantern / Drop Pipe
X: Mute Audio

The Entities

The Chorus (C): Blind, screaming miners with unhinged jaws. They hunt purely by sound. Throw an Audio Tape to distract them.
The Surveyor (S): Pale, lobotomized scientists in lead-lined coats. They ignore sound, patrolling mathematically. If they catch you, they will pin you down and surgically disassemble you.
The Attuned (A): Cable and bone grown together. Slow, but feels your vibration through the floor. Guards the Core.

Technical Details

100% Vanilla ES6. No frameworks, no libraries, no dependencies.
Single HTML File. The entire game—engine, UI, audio synthesis, map generation, and combat logic—lives in one file. Just open it in a browser.
WebAudio API: All sound effects (the heartbeat thumps, the alarm blares, the interface ticks) are synthesized procedurally in real-time. No audio assets are loaded.

Lore Premise

In 1984, the Soviet deep-earth research facility ONYX-7 breached a subterranean granite void at 4,200 meters. They didn't hit magma; they hit an ancient, acoustic chamber. A continuous ultra-low frequency infrasound (5.82 Hz) began radiating outward. The Pulse matches the resonant frequency of human bone marrow. It forces the mind to fracture into two extremes: pure visceral panic, or cold, calculating hostility. You are the latest subject to descend.
