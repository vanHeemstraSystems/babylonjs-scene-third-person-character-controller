babylonjs-scene-third-person-character-controller
# BabylonJS Scene - Third Person Character Controller

This repository stores the BabylonJS Scene ```Third Person Character Controller```.

It is being referenced from [BabylonJS Third Person Character Controller](https://github.com/vanHeemstraSystems/babylonjs-third-person-character-controller).

The idea is to separate the *scenes* from the *framework* that uses these scenes, so one can develop scenes separately and independently from the framework.

Take into account "Optimizing a Large-Scale Babylon.js Scene" at https://joepavitt.medium.com/optimizing-a-large-scale-babylon-js-scene-9466bb715e15 and "Optimizing Your Scene" at https://doc.babylonjs.com/features/featuresDeepDive/scene/optimize_your_scene

See an example of a very large scene at https://www.ibm.com/resources/cloud/mayflower-ship-experience/#/experience/harbor and how it was built at https://joepavitt.medium.com/building-the-web-based-3d-digital-experience-for-the-mayflower-autonomous-ship-a56f08e6558

## 100 - Introduction

## 200 - Requirements

## 300 - Building Our Application

You can download the ```scene.ts``` file from a remote application with the following URL: https://github.com/vanHeemstraSystems/babylonjs-scene-third-person-character-controller/raw/main/scene.ts

Example code:

```
...
  import { ThirdPersonCharacterController } from "https://github.com/vanHeemstraSystems/babylonjs-scene-third-person-character-controller/raw/main/scene.ts";
...
```

In case you get this error: 

```
ERROR in external "https://github.com/vanHeemstraSystems/babylonjs-scene-third-person-character-controller/raw/main/scene.ts"
The target environment doesn't support dynamic import() syntax so it's not possible to use external type 'module' within a script
```

To dynamically import ES modules you'll need to change webpack's output type to ESM:

```

```

Alternatively you could try ignoring the external import with ```webpackIgnore```:

```
/* webpackIgnore: true */
```

## 400 - Conclusion
