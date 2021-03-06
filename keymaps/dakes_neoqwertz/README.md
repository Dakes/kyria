# NeoQwertz
https://neo-layout.org/Layouts/neoqwertz/  

To use this, you will have to activate a german keyboard layout.  
If you are not using Linux, change the line: 
`#define UNICODE_SELECTED_MODES UC_LNX`  
in `config.h` according to your operating system. 

The Function Layer will activate, when either LAY3 and LAY5, LAY4 and LAY6 or LAY3 and LAY4 are pressed. 
### Layer 1: Base Layer

```
,-------------------------------------------.                              ,-------------------------------------------.
|LAY3/tab|   Q  |   W  |   E  |   R  |   T  |                              |   Z  |   U  |   I  |   O  |   P  |Ü/AltGr |
|--------+------+------+------+------+------|                              |------+------+------+------+------+--------|
| LShift |   A  |   S  |  D   |   F  |   G  |                              |   H  |   J  |   K  |   L  |   Ö  |Ä/RShift|
|--------+------+------+------+------+------+-------------.  ,-------------+------+------+------+------+------+--------|
| LCtrl  |   Y  |   X  |   C  |   V  |   B  | LAY5 | LAY6 |  | LAY5 | LAY6 |   N  |   M  | , ;  | . :  | - _  | ß/RCtl |
`----------------------+------+------+------+------+------|  |------+------+------+------+------+----------------------'
  encoder: skip tracks | Play | GUI  | LALT | Space| Enter|  | Enter| Space| Bksp | Del  | Mute | encoder: volume
                  ---> |      |      |      | LAY3 | LAY4 |  | LAY3 | LAY4 |      |      |      | <---
                       `----------------------------------'  `----------------------------------'
```

### Layer 2: shift layer
Same as Layer 1, activated with shift. (default shift)

### Layer 3: Symbols
```
,-------------------------------------------.                              ,-------------------------------------------.
|        |   °  |   _  |   [  |   ]  |   ^  |                              |   !  |   <  |   >  |   =  |   &  |   §    |
|--------+------+------+------+------+------|                              |------+------+------+------+------+--------|
|        |   \  |   /  |   {  |   }  |   *  |                              |   ?  |   (  |   )  |   -  |   :  |   @    |
|--------+------+------+------+------+------+-------------.  ,-------------+------+------+------+------+------+--------|
|        |   #  |   $  |   |  |   ~  |   `  |      |      |  |      |      |   +  |   %  |   "  |   '  |   ;  |   €    |
`----------------------+------+------+------+------+------|  |------+------+------+------+------+----------------------'
                       |      |      |      |      |      |  |      |      |      |      |      |
                       |      |      |      |      |      |  |      |      |      |      |      |
                       `----------------------------------'  `----------------------------------'
```

### Layer 4: Navigation and Numpad
```
,-------------------------------------------.                              ,-------------------------------------------.
|   esc  | PgUp | Bksp |  up  | del  | PgDn |                              |   *  |   7  |   8  |   9  |   +  |   -    |
|--------+------+------+------+------+------|                              |------+------+------+------+------+--------|
|        | home | left | down | right| end  |                              |   /  |   4  |   5  |   6  |   ,  |   .    |
|--------+------+------+------+------+------+-------------.  ,-------------+------+------+------+------+------+--------|
|        |  esc |  tab |insert| enter|undo  |      |      |  |      |      |   :  |   1  |   2  |   3  |   ;  |   =    |
`----------------------+------+------+------+------+------|  |------+------+------+------+------+----------------------'
                       |      |      |      |      |      |  |      |   0  |      |      |      |
                       |      |      |      |      |      |  |      |      |      |      |      |
                       `----------------------------------'  `----------------------------------'
```

### Layer 5: Small greek letters
```
,-------------------------------------------.                              ,-------------------------------------------.
|        |   ϕ  |   ω  |   ε  |   ρ  |   τ  |                              |   ζ  |   ψ  |   ι  |   ο  |   π  |    ς   |
|--------+------+------+------+------+------|                              |------+------+------+------+------+--------|
|        |   α  |   σ  |   δ  |   φ  |   γ  |                              |   ψ  |   θ  |   κ  |   λ  |   ε  |    η   |
|--------+------+------+------+------+------+-------------.  ,-------------+------+------+------+------+------+--------|
|        |   υ  |   ξ  |   χ  |   π  |   β  |      |      |  |      |      |   ν  |   μ  |   ϱ  |   ϑ  |   ⟨  |    ⟩   |
`----------------------+------+------+------+------+------|  |------+------+------+------+------+----------------------'
                       |      |      |      |      |      |  |      |      |      |      |      |
                       |      |      |      |      |      |  |      |      |      |      |      |
                       `----------------------------------'  `----------------------------------'
```

### Layer 6: Big greek letters and Mathematical Symbols
```
,-------------------------------------------.                              ,-------------------------------------------.
|        |   ℚ  |   Ω  |   ∃  |   ℝ  |   ∂  |                              |   ℤ  |   ⊂  |   ∫  |   ∈  |   Π  |    ∪   |
|--------+------+------+------+------+------|                              |------+------+------+------+------+--------|
|        |   ∀  |   Σ  |   Δ  |   Φ  |   Γ  |                              |   Ψ  |   Θ  |   ×  |   Λ  |   ∩  |    ℵ   |
|--------+------+------+------+------+------+-------------.  ,-------------+------+------+------+------+------+--------|
|        |   ∇  |   Ξ  |   ℂ  |   √  |   ⇐  |      |      |  |      |      |   ℕ  |   ⇔  |   ⇒  |   ↦  |   ∞  |    ∅   |
`----------------------+------+------+------+------+------|  |------+------+------+------+------+----------------------'
                       |      |      |      |      |      |  |      |      |      |      |      |
                       |      |      |      |      |      |  |      |      |      |      |      |
                       `----------------------------------'  `----------------------------------'
```

### Function Layer: F-keys, RGB control and media buttons
```
,-------------------------------------------.                              ,-------------------------------------------.
|        | F1   |  F2  | F3   | F4   | F5   |                              | F6   |  F7  |  F8  |  F9  | F10  |  F11   |
|--------+------+------+------+------+------|                              |------+------+------+------+------+--------|
|        | TOG  | SAI  | HUI  | VAI  | MOD  |                              | VolUp|  F4  |  F5  |  F6  | F11  |  F12   |
|--------+------+------+------+------+------+-------------.  ,-------------+------+------+------+------+------+--------|
|        |      | SAD  | HUD  | VAD  | RMOD |      |      |  |      |      | VolDn|  F1  |  F2  |  F3  | F12  |        |
`----------------------+------+------+------+------+------|  |------+------+------+------+------+----------------------'
                       |      | Prev | Next |      |      |  |      |      | Prev | Next |      |
                       |      |      |      |      |      |  |      |      |      |      |      |
                       `----------------------------------'  `----------------------------------'
```
