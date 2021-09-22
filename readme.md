# Nuvem de Som

Soundcloud searcher

## Install

```bash
pip install nuvem_de_som==0.0.1a1
```

## Usage

```python
from nuvem_de_som import SoundCloud

for r in SoundCloud.search("piratech"):
    print(r)
    
"""
{'artist': 'Piratech',
 'duration': 211.559,
 'image': 'https://i1.sndcdn.com/artworks-000047298601-0av6vy-original.jpg',
 'title': "Johnny Mathis  It's Not For Me To Say ( Piratech Re beat )",
 'uri': 'https://cf-media.sndcdn.com/9vsicX1CAuk4.128.mp3?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiKjovL2NmLW1lZGlhLnNuZGNkbi5jb20vOXZzaWNYMUNBdWs0LjEyOC5tcDMqIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxNjMyMzMxNzgxfX19XX0_&Signature=WSipahJC0FCgxfvpdoky1WpTgeHNqPT-gtNPE7tbUpphPTKCqpmLoTP-D3aooSq0tzvF-tlNaY5vox9JPutLdEkfD-HhPA85SoRlsk3HcjHgNMHB2BWfMCGKVYQMntzPmxD4xsx~yKU18HLuUefn5ar1knQHJJCRcz2jgMdD94IGDpsVZl-G8ugTww6YRCgRNeb08yVZEejJ2sD0VhB1uRsncNNbAVSm~6yM7ZmyDCH~eowIzO2y6gsKDn6Cg9BCIaA3Tomp2sYEqDbjaLst-uqPE4HyA4HUtQlI51HhvLtcGVnjtjXbM~wkhprsLqMT51b9f7OyrX3C29AQb1rThw__&Key-Pair-Id=APKAI6TU7MMXM5DG6EPQ',
 'url': 'https://soundcloud.com/acidkid/johnny-mathis-its-not-for-me'}
"""
```