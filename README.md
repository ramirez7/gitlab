# gitlab
Links to my GitLab projects

- [`sdl-gpu-hs`](https://gitlab.com/macaroni.dev/sdl-gpu-hs) - Haskell FFI bindings for the `sdl-gpu` C 2D graphics library. 
  - Within it is [`memorable`](https://gitlab.com/macaroni.dev/sdl-gpu-hs/-/blob/master/src/Memorable.hs), a WIP library for zero-alloc FFI. And eventually, manually-managed, off-heap, type-safe Haskell data structures.
  - Also includes [bindings to `SDL_FontCache`](https://gitlab.com/macaroni.dev/sdl-gpu-hs/-/blob/master/src/SDL/GPU/FC/C.hsc) (a C text graphics library written by the author of `sdl-gpu`)
- [`cute-c2-hs`](https://gitlab.com/macaroni.dev/cute-c2-hs) - Haskell FFI bindings to `cute_c2`, a single-header C collision detection library.
- [`cute-sound-hs`](https://gitlab.com/macaroni.dev/cute-sound-hs) - Haskell FFI bindings to `cute_sound`, a single-header C audio library.
- [`gamedev-scratch`](https://gitlab.com/macaroni.dev/gamedev-scratch) - Multiple Ludum Dare game jam entries (built with Haskell)
  - [*Echoes of Ouroboros*, a loopy puzzle game. Built in 72 hours for Ludum Dare 47 (Theme: "Stuck in a Loop")](https://ldjam.com/events/ludum-dare/47/echoes-of-ouroboros)
  - [*I'm Definitely Not Scared of My Own Basement*, an unconventional rail shooter. Built in 72 hours for Ludum Dare 48 (Theme: "Deeper and Deeper")](https://ldjam.com/events/ludum-dare/48/im-definitely-not-scared-of-my-own-basement)
  - In a private repository, there is [*Nuclear Puzzle Defense*, a puzzle game/shmup mashup. Built in 72 hours for Ludum Dare 49 (Theme: "Unstable")](https://ldjam.com/events/ludum-dare/49/nuclear-puzzle-defense)
- [`slippi-netplay-nix`](https://gitlab.com/ramirez7/slippi-netplay-nix) - A constantly-updated Nix derivation for the Slippi fork of the Dolphin emulator (used to play Super Smash Bros Melee online.)
- [`userfaultfd-haskell`](https://gitlab.com/ramirez7/userfaultfd-haskell) - Incomplete & experimental Haskell FFI bindings to [`userfaultfd`](https://www.kernel.org/doc/html/latest/admin-guide/mm/userfaultfd.html), a relatively new Linux feature allowing for userland page fault handling. It includes a little demo as well. 
