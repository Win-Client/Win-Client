# 🧪 Potion Win-Client Modules & Features

Welcome to the comprehensive module catalog for the ultimate **Potion Win-Client** (Minecraft Fabric). Below is an exhaustive list of our robust, state-of-the-art modules engineered for seamless utility, unmatched combat precision, and unparalleled performance.

---

## ⚡ Combat
Our combat suite is built for precise hits, automated tactics, and total control over fight dynamics.

*   **AimAssist**: Subtle, customizable camera correction that gently aligns your crosshair with targets without looking artificial.
*   **AutoBlock**: Dynamically manages sword blocking during engagements to shield against damage while maximizing counter-strike potential.
*   **AutoCrystal**: Extremely rapid end crystal placement and detonation logic optimized for low-latency target eradication.
*   **AutoRod**: Instantly flips to your fishing rod and hooks targets for optimal combo initiation and speed suppression.
*   **Backtrack**: Artificially buffers opponent position packets to let you land hits on their historical positions, bypassing standard range dynamics.
*   **ComboTap**: Perfect W-tap / S-tap timing synchronization to consistently deal increased knockback and keep opponents locked in combos.
*   **Criticals**: Forces critical hits on every jump or micro-jump, multiplying your damage output effortlessly.
*   **HitSelect**: Delays attacks until the exact frame the opponent's damage ticks expire, ensuring 100% of your hits register successfully.
*   **HitSwap**: Seamlessly alternates weapon slots or configurations dynamically depending on target proximity and armor status.
*   **KeepSprint**: Cancels the sprint-reset slowdown when striking targets to maintain maximum momentum.
*   **KnockbackDelay**: Alters packet flow to fine-tune the exact millisecond you receive knockback, disrupting standard combo timing.
*   **KnockbackDisplacement**: Modifies server-side position registers to redirect knockback trajectory or reduce its intensity.
*   **LeftClicker**: Ultra-configurable autoclicker with highly sophisticated randomization to mimic human click distributions and bypass click-rate checks.
*   **NoHitDelay**: Removes client-side weapon swing limitations for maximum attack speed responsiveness.
*   **Reach**: Cleanly extends your interactive reach distance within safe server boundaries.
*   **Refill**: Swiftly restocks hotbar items (such as potions, soups, or golden apples) directly from your inventory.
*   **RightClicker**: High-speed, humanized right-click automation for blocks, projectiles, or consumable items.
*   **SilentAura**: A highly advanced combat aura that targets opponents silently behind the scenes without snapping your client-side camera view.
*   **TriggerBot**: Automatically clicks the moment a valid target enters your crosshair boundaries.
*   **Velocity**: Highly adjustable knockback dampening system (vertical and horizontal scaling from 0% to 100%).

---

## 🌪️ Anarchy
Engineered to dominate server environments with zero rules and brutal playstyles.

*   **CrystalAura**: High-frequency crystal placement and detonation targeted specifically at players, supporting multiple placements per tick.
*   **KillAura**: The classic, customizable combat machine. Features multi-target sorting, smart blocking, pathfinding assistance, and angle smoothing.

---

## 🏃 Movement
High-speed navigation, evasion, and momentum utilities.

*   **Flight**: Zero-gravity locomotion to traverse vast gaps or scale heights with customizable speed profiles.
*   **NoFall**: Dynamically negates fall damage through smart packet modification or spoofed ground-state checks.
*   **NoJumpDelay**: Removes the standard vanilla cooldown between consecutive jumps.
*   **NoPush**: Bypasses player, entity, and liquid push forces to keep you perfectly on track.
*   **Parkour**: Automatically jumps at the absolute edge of blocks to maximize leap distances.
*   **Speed**: Massive velocity boosters featuring multiple bypass methods (Bhop, Strafe, Ground-glide).
*   **Sprint**: Keeps sprinting active continuously without manual keybind holding.
*   **Timer**: Directly manipulates client ticks to speed up or slow down all client-side physical actions.

---

## 👤 Player
Self-preservation, metadata manipulation, and client integrity.

*   **AntiExploit**: Blocks dangerous incoming packets, crash attempts, or unauthorized server commands.
*   **Blink**: Temporarily suspends outbound packet transmission, allowing you to "teleport" or position yourself invisibly.
*   **CustomRank**: Visually changes your scoreboard/chat rank local to your client view.
*   **FakeLag**: Simulates latency spikes to make your movements unpredictable to opponents and server anticheats.
*   **NameHider**: Protects your identity during recording or streaming by masking your username.

---

## 🛠️ World
Environment interaction and automated construction.

*   **AutoPlace**: Instantly places blocks on targeted faces without requiring manual click inputs.
*   **BedBreaker**: Automatically targets and destroys bed blocks through walls for rapid game-ending actions in BedWars.
*   **ChestAura**: Silently opens container blocks around you without needing visual interaction.
*   **ChestStealer**: Blazing-fast item extraction from open chests, complete with smart category sorting.
*   **Clutch**: Automatically places safety blocks (blocks or webs) beneath you when falling over voids.
*   **FastPlace**: Disables the default right-click block placement delay.
*   **Scaffold**: Fluidly bridges blocks directly under your feet as you walk, run, or sprint in any direction.

---

## 🔮 Utility
Convenient helpers and automated safety features.

*   **AntiFireball**: Instantly deflects incoming ghast or player-thrown fireballs within range.
*   **AutoTotem**: Automatically shifts Totems of Undying into your offhand slot from any inventory location when health drops below thresholds.
*   **InventoryManager**: A powerhouse module that dynamically cleans, discards trash, and auto-equips the best armor/weapons in real time.

---

## 📺 HUD & Render
Stunning visuals and crucial environmental awareness overlays.

*   **Animations**: Custom 1.7-style and modern block-hitting / sword-swing visual customizer.
*   **PlayerESP**: Highly distinct glowing, box, or skeleton overlays to pinpoint opponent locations through any solid terrain.
*   **RiceFarmer**: Specialized overlay/helper for farming mechanics.
*   **BedPlates**: Renders clear status indicators above active beds.
*   **ModulesList**: A sleek, beautifully animated list of active modules displayed directly on your screen.
*   **ScaffoldInfo**: Displays current block counts and bridging metrics directly while scaffolding.
*   **TargetHud**: A premium, dynamic widget displaying health, distance, and armor status of the target you are actively engaging.

---

## 🎮 Minigames
Specialized automation for custom game modes.

*   **PartyGames**: Automatically solves, guides, or optimizes gameplay during server party minigame challenges.

---

## ⚙️ Core & Settings
*   **ClickGui**: The beautiful, highly responsive visual control dashboard to configure and toggle everything.
*   **Colour**: Custom color styling config, supporting smooth pastel blends, custom RGB gradients, and modern dark themes.
*   **Font**: Smooth rendering system swapping out the pixelated default fonts for ultra-sleek typography.
*   **Rotations**: Core rotation manager handling custom head-snapping, vector calculations, and anti-cheat checks.
*   **TargetFilter**: Custom filter determining priority target orders (health, distance, threat levels).
