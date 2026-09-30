# Research Notes

This build follows the supplied master prompt. Current Three.js documentation confirms WebGLRenderer uses WebGL 2 and the animation system supports AnimationMixer, cross-fades and synchronized AnimationClips. For this first implementation, network asset acquisition was not available through npm, so the build uses the prompt's explicit procedural fallback: authored primitives, procedural motion, procedural materials, and Web Audio.

Chosen defaults: 60 Hz fixed simulation; 12-frame base deflect window; 4-frame spam floor; 100/120 posture; 60-frame posture recovery delay; vitality-scaled recovery; 3-hit player chain; nine enemy moves including thrust, sweep and grab.
