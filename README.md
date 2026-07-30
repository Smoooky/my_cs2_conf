# How to use
1. Download `myconf.cfg`
2. Save `myconf.cfg` to:   
```
C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
```
3. Execute this commmand in cs2 terminal:
```
exec myconf.cfg
```
# To boost your FPS
*Main Video Tab*
- Display Mode: Fullscreen
- Refresh Rate: Max available
*Advanced Video Tab*
- Boost Player Contrast: Enabled
- V-Sync: Disabled
- Multi-Sampling Anti-Aliasing (MSAA): 2x MSAA
- Global Shadow Quality: Medium
- Model / Texture Detail: Medium
- Shader Detail: Low
- Particle Detail: Low
- Ambient Occlusion: Disabled
- High Dynamic Range (HDR): Performance
- FidelityFX Super Resolution (FSR): Disabled 
- NVIDIA Reflex Low Latency: Enabled + Boost

#  Steam Launch Options
```
-nojoy -novid -high +fps_max 0 +engine_low_latency_sleep_after_client_tick true
```