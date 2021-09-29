# sword

Swords are items that you can wield to do damage on objects and NPCs in the world.



## `.metaversefile` Wearable

![](https://i.imgur.com/f1cjF55.png)

![](https://i.imgur.com/0sJXsd2.png)

The `.metaversefile` goes in the directory with the GLB file in order to create the XRpackage.


```
{
  "name": "sword",
  "description": "Sword XRPackage",
  "start_url": "sword.glb",
  "components": [
    {
      "type": "wear",
      "position": [0, 0, 0]
    }
  ]
}
```

## `.metaversefile` Wield

![](https://i.imgur.com/SaXNpC6.png)

```
{
  "name": "saber",
  "description": "Saber XRPackage",
  "start_url": "index.js",
  "components": [
    {
      "type": "use",
      "subtype": "swing",
      "useAnimation": "slash"
    }
  ]
}
```
