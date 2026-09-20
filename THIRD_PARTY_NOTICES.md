# Third-Party Notices

This is a binary-distribution repository. Public availability does not grant
an open-source license to the original application or its assets. Dependency
licenses and any separately granted rights remain in effect.

## Runtime Components

| Component | License |
| --- | --- |
| [Filament and gltfio 1.75.1](https://github.com/google/filament) | [Apache 2.0](licenses/filament.txt) |
| [gdx-ai 1.8.2](https://github.com/libgdx/gdx-ai) | [Apache 2.0](licenses/gdx-ai.txt) |
| [libGDX core 1.13.1](https://github.com/libgdx/libgdx) | [Apache 2.0](licenses/libgdx.txt) |
| [AndroidX Core 1.18.0](https://android.googlesource.com/platform/frameworks/support/) | [Apache 2.0](licenses/androidx-core.txt) |

The water-surface normal calculation adapts `gerstner_wave_normal` from
[osgw](https://github.com/CaffeineViking/osgw/blob/1d82fbeaabc1c04e8bed88b4dd27e0c690065dc8/share/shaders/gerstner.glsl),
copyright 2018 Erik Sven Vasconcelos Jansson, under the [MIT License](licenses/osgw.txt).

## Generated Scene Assets

The scene combines project-authored geometry and animation with AI-generated
visual studies. Fish and reef studies use [TripoSG](https://github.com/VAST-AI-Research/TripoSG)
geometry ([MIT License](licenses/triposg.txt)) and Hunyuan3D 2.1 texture output
([Community License](licenses/hunyuan3d-2.1.txt)). The latter's terms include
territorial restrictions addressing generated outputs. Those restrictions
remain unresolved for this distribution; no additional rights or clearance
are implied by publication. The app is not affiliated with or endorsed by Tencent.

The nine-variant Acanthastrea texture was newly generated with Codex's built-in
image tool, informed by four user-provided photographs. These photographs are
references, not directly packaged texture maps. The fourth reference bears
© Happy Reef; no separate free photo licence was supplied, and generation does
not transfer rights to those references. The polyp geometry and fluorescence
patterns are project-authored. No CC0 or other third-party free licence is
asserted for the generated texture.

Earlier AI references and the launcher icon were generated for the project. No assets,
code or video frames from Maxelus Ocean Aquarium are included. Offline model
weights and generation software are not bundled in the Android application.

The complete license texts are also preserved inside the published APKs.
Development notes and detailed generation records are maintained privately.
