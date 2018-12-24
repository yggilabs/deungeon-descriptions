# deungeon-descriptions
Generate dungeon description files of various formats from structured data.

Structured data can be found [here](https://github.com/yggilabs/dungeon-descriptions/blob/master/_data/dungeons.yml). The format is in YAML but JSON or CSV files could work. here is a sample:

```yaml
- name: Fair Wilds
  desc: 
    - Untamed and unscouted woods
    - Known for peace and pleasant sights
  tags:
    - easy
    - early game
    - grassland aesthetic
    
- name: Teeming pasture
  desc: 
    - An overgrown grazing field
    - Filled with countless swarms of insects
  tags:
    - vermin majority
    - grassland aestheitc
    - fey enemies
```

Output files should be automatically generated on any commit. Currently, there are three examples of output
* [.html](https://yggilabs.github.io/dungeon-descriptions/index.html) (*[source](https://github.com/yggilabs/dungeon-descriptions/edit/master/index.md)*)
* [.txt](https://yggilabs.github.io/dungeon-descriptions/index.txt) (*[source](https://github.com/yggilabs/dungeon-descriptions/edit/master/index.txt)*)
* [.json](https://yggilabs.github.io/dungeon-descriptions/index.json) (*[source](https://github.com/yggilabs/dungeon-descriptions/edit/master/index.json)*)
