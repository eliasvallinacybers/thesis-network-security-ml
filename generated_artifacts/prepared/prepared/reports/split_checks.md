# QA del split
- **Tier**: Tier 3 | **SALT**: 347222276 | **bins**: 160000
- **Ratios objetivo**: {'train': 0.7, 'val': 0.15, 'test': 0.15}
- **Claves únicas**: 34,956 | **Keys por split**: {'train': 24367, 'val': 5297, 'test': 5292}

## Checks
- Desvío tamaño TRAIN (pp): 9.894 (límite 10.0) → OK
- Desvío tamaño VAL (pp): 2.205 (límite 10.0) → OK
- Desvío tamaño TEST (pp): 7.689 (límite 10.0) → OK
- Gap VAL–TRAIN (pp): 7.449 (límite 16.0) → OK
- Rango prevalencias (pp): 19.488 (límite 20.0) → OK