# Nuvem de Som

Soundcloud searcher

## Install

```bash
pip install nuvem_de_som==0.0.1a2
```

## Usage

```python
from nuvem_de_som import SoundCloud

for r in SoundCloud.search_tracks("piratech nuclear chill", 
                                  extract_streams=True):
    print(r)
    break

for p in SoundCloud.search_people("piratech", extract_streams=True):
    print(p)
    break

for p in SoundCloud.search_sets("piratech", extract_streams=True):
    print(p)
    break

for p in SoundCloud.search("heavy metal", extract_streams=True):
    print(p)
    break
```