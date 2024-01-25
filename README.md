aframe-obj-tetra
==

Example OBJ file with material displayed using A-Frame.

## Usage

On a Mac:

```sh
python3 -m http.server 8000
```

Then browse to:

* http://localhost:8000/

* * *

## tetrahedron.obj

```obj
# tetrahedron.obj
# Author: Mitch Allen

mtllib colors.mtl

v 0.000000 0.000000 0.000000
v 1.000000 0.000000 0.000000
v 0.500000 0.866000 0.000000
v 0.500000 0.288700 0.816500

usemtl green1
f 3 2 1

usemtl red1
f 1 2 4

usemtl blue1
f 2 3 4

usemtl purple1
f 4 3 1
```

