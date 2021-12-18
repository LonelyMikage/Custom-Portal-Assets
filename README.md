# Custom Portal Assets
A compilation of custom portal assets from minor texture changes to complete text overhauls

Credits:
- ThatBeanLady		rainbow camera texture
- Lia/Nick/idk		darude dinosaur.wav
- NAHTAIV3L		minor detail work on the cube textures
- Halosnow		provided their many textures and ihud
- Cosine		provided their transparent portalgun
- SaltyJerms		provided their salt cube
- nonsensicalalias	provided their textures and ihud

--- Contents: ---

- ihud configs --- cfg files with custom ihud settings
- models --------- playermodels and viewmodels
- sound	---------- various sounds
- materials ------ textures
- particles ------ customised particles
- others --------- anything that doesn't fall into the above folders

--- ihud configs ---

- halo ----- letterless trans + ace ihud
- Mikage --- letterless trans ihud
- non ------ letterless nonsensical purple ihud

--- models ---

- Mikage --- error playermodel **note that its a broken model, not a model of an error sign**

--- other ---

- Mikage Text -------- customised texts
- ClientScheme.res --- mixed pride colours hud

--- particles ---

- portal_projectile.pcf -------- trans traveling portal particles
- portal_projectile_dx80.pcf --- part of portal_projectile
- portalgun.pcf ---------------- trans portalgun lights
- portalgun_dx80.pcf ----------- part of portalgun

--- sound ---

- dinosaur1 ----------- darude 00/01 radio transmission
- looping_radio_mix --- still alive ragtime cover by Vandoorea (can be found here: https://www.youtube.com/watch?v=EBiO95Nj9-)
- portal_open(1-3) ---- tf2 default hitsound

--- materials ---

default mask = less glowy

effects\
- redlaser1.vtf --------- pink turret laser
- redlaser1_smoke.vtf --- pink turret laser

models\
- props\
  - autoportal_frame\autoportal_frame.vtf --- polyam portal frame
  - bts_bed\bts_bed.vtf --------------------- snorlax ratman bed
  - cake\cake.vtf --------------------------- pride cake
  - claw\claw.vtf --------------------------- enby claw
  - elevator_caps.vtf\elevator_caps.vtf	----- ace purple ele step
  - food_can\food_can.vtf ------------------- ThatBeanLady beans
  - kb_mouse\kb_mouse.vtf ------------------- ace purple kb + trans mouse
  - lab_chair\lab_chair.vtf ----------------- lesbian chair
  - milk_carton\milk_carton.vtf ------------- trans & Rippy milk carton
  - water_bottle\water_bottle.vtf ----------- El Korgus water

  - ball_catcher_sheet.vtf --------- trans orb catcher
  - Bed01.vtf ---------------------- enby vault bed
  - Bed01[masked].vtf -------------- Bed01 with the default mask
  - bed01_glass.vtf ---------------- purple vault bed glass
  - Box_dropper.vtf ---------------- enby cube dropper
  - button.vtf --------------------- ace cube button
  - button[halo].vtf --------------- blue cube button
  - clock.vtf ---------------------- polyam vault clock
  - clock[masked].vtf -------------- clock with the default mask
  - combine_ball_launcher.vtf ------ trans orb launcher
  - door_01.vtf -------------------- enby chamber door
  - door_02.vtf -------------------- enby orb door
  - door_02_a.vtf ------------------ door_02 with 1 dot
  - door_02_b.vtf ------------------ door_02 with 2 dots
  - Glados_stairs.vtf -------------- lesbian glados platform
  - Glados_stairs_glass.vtf -------- glass for Glados_stairs
  - Lift_platform.vtf -------------- lesbian lift
  - Light Rail\ -------------------- enby light rail textures
    - Light_rail_corner.vtf
    - Light_rail_endcap.vtf
    - Light_rail_endcap_glass.vtf
    - Light_rail_wall_emitter.vtf
  - Light_rail_platform.vtf -------- lesbian moving platform
  - metal_box.vtf ------------------ trans cube
  - metal_box[masked].vtf ---------- metal_box with the default mask
  - metal_box[halo].vtf	------------ purple cube
  - metal_box[haloMasked].vtf ------ metal_box[haloMasked] with the default mask
  - metal_box[non].vtf ------------- bi cube
  - metal_box[SaltyJerms].vtf ------ salt logo cube
  - metal_box_skin001.vtf ---------- ace companion cube
  - metal_box_skin001[non].vtf ----- bi companion cube
  - pedestal.vtf ------------------- trans pink pedestal
  - pedestal_glass.vtf ------------- ace purple pedestal glass
  - portal_cleanser.vtf ------------ trans fizzler
  - radio.vtf ---------------------- trans radio
  - radio[halo].vtf ---------------- purple radio
  - radio[non].vtf ----------------- bi radio
  - Round_elevator_sheet_1.vtf ----- ace ele interior
  - Round_elevator_sheet_2.vtf ----- trans ele lights
  - Round_elevator_sheet_3.vtf ----- lesbian ele sign
  - Security_Camera.vtf ------------ rainbow camera
  - Sphere.vtf --------------------- rainbow sphere
  - sphere_lit.vtf ----------------- part of sphere
  - switch001.vtf ------------------ trans use button
  - table.vtf ---------------------- bi vault table
  - toilet.vtf --------------------- pan toilet
  - Turret_01.vtf ------------------ ace turret
  - Turret_01_inactive.vtf --------- part of Turret_01
  - Turret_01[halo].vtf	------------ red turret
  - Turret_01_inactive[halo].vtf --- part of Turret_01[halo]
  }

- props_animsigns\
  - awe_total.vtf ----------- Mikage custom chamber sign
  - newsignage_back02.vtf --- trans chamber sign bg

- props_bts\
  - glados_ball_01.vtf --------------- ace purple core
  - glados_ball_01[masked].vtf ------- glados_ball_01 with default mask
  - glados_ball_01[lesb].vtf --------- lesbian purple core
  - glados_ball_01[lesbMasked].vtf --- glados_ball_01[lesb] with default mask
  - glados_ball_01[non].vtf ---------- nonsensical purple core
  - glados_ball_02.vtf --------------- lesbian orange core
  - glados_ball_02[masked].vtf ------- glados_ball_02 with default mask
  - glados_ball_03.vtf --------------- trans pink core
  - glados_ball_03[masked].vtf ------- glados_ball_03 with default mask
  - glados_ball_03[canteven].vtf ----- canteven red core
  - glados_ball_04.vtf --------------- trans blue core
  - glados_ball_04[masked].vtf ------- glados_ball_04 with default mask
  - glados_body.vtf ------------------ ace glados

- props_junk\garbage003a_01.vtf --- trans mug
  **located in hl2\materials\

- weapons\
  - v_models\v_portalgun\
    - transparent gun [cosine]\
      - v_portalgun.vmt ---------------- vmt file to make pg transparent
      - v_portalgun_animated[rb].vtf --- animated rainbow portalgun
      - v_portalgun_animated[tg].vtf --- animated trans portalgun
        **put v_portalgun_animated textures in materials\animated\

    - v_portalgun.vtf --------------- LonelyMikage's portalgun
    - v_portalgun[green].vtf -------- green portalgun
    - v_portalgun[halo].vtf --------- Halosnow's portalgun
    - v_portalgun[haloOld].vtf ------ Halosnow's old portalgun
    - v_portalgun[Soviet].vtf ------- USSR flag portalgun
    - v_portalgun[SovScuffed].vtf --- same thing but scuffed

  - w_models\portalgun\
    - w_portalgun.vtf ---------- LonelyMikage's portalgun
    - w_portalgun[green].vtf --- green portalgun
    - w_portalgun[halo].vtf ---- Halosnow's portalgun

nature\
- pony goo -------------------- mlp goo **only works on dx90
- escape_vista_01.vtf --------- Jeff Nachtigall pixel art tribute
- escape_vista_02.vtf --------- part of escape_vista_01
- hazard_liquid.vtf ----------- ace purple goo
- hazard_liquid.beneath.vtf --- part of hazard_liquid
- hazard_liquid[halo].vtf ----- twitter meme goo

signage\
- indicator_lights\ --- trans power lights
  - indicator_lights_corner_floor.vtf
  - indicator_lights_corner_floor001.vtf
  - indicator_lights_corner_wall.vtf
  - indicator_lights_floor.vtf
  - indicator_lights_wall.vtf

- overlay_aperture_logo_worn.vtf ------------- Source Done Proud Logo
- signage_arrow.vtf -------------------------- rainbow arrow
- signage_doorstate.vtf ---------------------- part of indicator_lights
- signage_exit.vtf --------------------------- Rippy exit sign
- signage-overlay_arrow.vtf ------------------ same thing as signage_arrow
- signage_overlay_boxdispenser.vtf ----------- updated to be the same as my texture(s)
- signage_overlay_boxhurt.vtf ---------------- updated to be the same as my texture(s)
- signage_overlay_cake.vtf ------------------- ace cake
- signage_overlay_catcher.vtf ---------------- updated to be the same as my texture(s)
- signage_overlay_companioncube.vtf ---------- updated to be the same as my texture(s)
- signage_overlay_companioncube_broken.vtf --- updated to be the same as my texture(s)
- signage_overlay_dots ----------------------- rainbow dots
  - signage_overlay_dots1.vtf
  - signage_overlay_dots2.vtf
  - signage_overlay_dots3.vtf
  - signage_overlay_dots4.vtf
- signage_overlay_energyball.vtf ------------- ace orb
- signage_overlay_fountain.vtf --------------- no Mikage sign
- signage_overlay_incinerator.vtf ------------ trans pink fire
- signage_overlay_toxic.vtf ------------------ overgoo sign
- signage_overlay_turret.vtf ----------------- updated to be the same as my texture(s)

sprites\
- bluelight.vtf ----- invisible portalgun orb
- orangelight.vtf --- invisible portalgun orb
