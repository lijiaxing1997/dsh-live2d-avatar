# Live2D licensing

This plugin bundles and adapts software and assets published by Live2D Inc.
None of them are covered by the plugin's own MIT license.

## Live2D Cubism Core

`assets/Core/live2dcubismcore.min.js` (and `assets/Core/LICENSE.md`) is
"Redistributable Code" under the Live2D Proprietary Software License Agreement:

- https://www.live2d.com/eula/live2d-proprietary-software-license-agreement_en.html

## Live2D Cubism Web Framework / sample application

`src/live2d/framework/**` and the `src/live2d/lapp*.ts` files are derived from
the Cubism SDK for Web sample application, used under the Live2D Open Software
License Agreement:

- https://www.live2d.com/eula/live2d-open-software-license-agreement_en.html

The files were copied from the AiChat project's vendored
`CubismSdkForWeb-5-r.4` (framework, r.4 era) and adapted: the sample's scene
list, HTTP model-manager API and its background/gear chrome were removed, the
renderer was reduced to a single headless viewer, and external mouth control
plus explicit load callbacks were added.

## Sample model

`assets/models/Hiyori/**` is the "Hiyori" sample model distributed with the
Cubism SDK. It is covered by the Live2D Free Material License Agreement:

- https://www.live2d.com/eula/live2d-free-material-license-agreement_en.html

It is bundled only so the plugin works out of the box. Replace or remove it
freely; point `extraModelsDirs` at your own models instead.
