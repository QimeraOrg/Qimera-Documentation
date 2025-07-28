---
sidebar_position: 3
title: Switching Scenes
---

- **Quick Switcher:** Press `F2` (default) to open the Scene palette, then click a Scene or use arrow keys + Enter.
- **Timeline Cue:** Drop a *Scene Cue* on the Trigger Timeline to automate during live shows.
- **External Trigger:** Send `osc:/qimera/scene/load <SceneName>` or use the REST endpoint `POST /api/scene/load`.

Scene changes are frame‑accurate; Qimera blends camera transforms and fades audio/video as needed to ensure seamless on‑air transitions.

## Best Practices

- **One purpose, one Scene.** Avoid “kitchen‑sink” Scenes; keep them focused on a single shot or location.
- **Version control.** Commit `.sceneasset` files whenever you tweak critical settings—rollbacks are lifesavers.
- **Pre‑flight test.** Load each Scene in rehearsal and verify cameras, media, and tracking before you go live.
- **Use tags wisely.** Prefix tags with show names (`NEWS_`, `SPORTS_`) to filter quickly during hectic broadcasts.

## Troubleshooting

| Symptom                             | Fix                                                                                   |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Scene loads but camera is incorrect | Make sure the correct Cine Camera Actor is *bound* in the Scene asset.               |
| Layer visibility ignored            | Confirm the actor is in a registered Layer Channel and **Include Layers** is enabled. |
| Media sources not refreshing        | Check that **Reload Media on Scene Load** is turned on in Scene settings.            |
| Long hitch during switching         | Pre‑warm large Nanite meshes or enable **Async Scene Load** in Preferences.          |


