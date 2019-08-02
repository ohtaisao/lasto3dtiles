# las-to-3d-tiles

## installation

```bash
pip install -r requirements.txt
pip install .
```

## example

```bash
lasto3dtiles LasSetTo3dTiles --input-dirname /path/to/lasdir --point-map-def /path/to/pointmap.json --workers 1 --voxel-size 0.05 --skip-rate 0.99
```

### pointmap.json 

```json
{
    "xy": [
        [-65888.225128783, -131468.75],
        [-65885.7235189955, -131439.625],
        [-65775.40252736639, -131378.5],
        [-65808.17361558274, -131387.375],
        [-65469.580730843525, -131206],
        [-65247.73245331616, -131060.5],
        [-65224.34240180296, -131047],
        [-64982.82421120412, -130901.5],
        [-64650.68721828719, -130766.375],
        [-64492.335318737925, -130742],
        [-64314.34578235673, -130674.5],
        [-64128.851416613004, -130633.375],
        [-63825.96571152608, -130537.375],
        [-63610.577108821635, -130428.25],
        [-63342.79636188023, -130220.125],
        [-63332.414681262075, -130204.5],
        [-63082.35970701867, -129867.875],
        [-63022.57123309723, -129745.75]
    ],
    "lonlat": [
        [137.77981920025078, 34.812789232327006],
        [137.77984466482883, 34.813052389078685],
        [137.7810414999973, 34.81361173201858],
        [137.7806836556636, 34.81351483823791],
        [137.78436797803553, 34.81519064416055],
        [137.7867807208993, 34.81650748219219],
        [137.7870380471617, 34.81663740319841],
        [137.78966594273942, 34.817975137236616],
        [137.79328861402763, 34.81921486148686],
        [137.79501886509422, 34.819430655275895],
        [137.79693816267363, 34.82003839801135],
        [137.79897532891783, 34.820440254422756],
        [137.8022785280416, 34.82131552393102],
        [137.8046337718052, 34.82231849428489],
        [137.80753539346225, 34.82421100332437],
        [137.80764663346108, 34.82434201310291],
        [137.81035614988534, 34.827391509570035],
        [137.81100625482898, 34.828502290876585]
    ]
}

```

## TODO

 - generate tileset.json
 - make `LasToPnts` task equality 
