

# J4 Scripts Advanced Drug Processing

# Chemicals Preview

![image](https://user-images.githubusercontent.com/82112471/165860380-861eddc3-8548-442d-b483-2afd311970ad.png)

# Cocaine Preview

![image](https://user-images.githubusercontent.com/82112471/165860461-66fb9e25-d507-4663-833b-dc658985276a.png)

# Hydrochloric Acid Preview

![image](https://user-images.githubusercontent.com/82112471/165860628-45a4959f-e795-44f5-909f-fcbeca8d2cc0.png)

# Sodium Hydroxide Preview

![image](https://user-images.githubusercontent.com/82112471/165860272-8461de69-562b-47a2-9541-21e20d005175.png)

# Sulfuric Acid Preview

![image](https://user-images.githubusercontent.com/82112471/165860175-93000475-6432-42cd-ab3c-387a98c4cbad.png)

# Weed Preview

![image](https://user-images.githubusercontent.com/82112471/165861162-cf19f312-92bb-4241-86a4-9cc07720773d.png)

# Heroin Preview

![image](https://user-images.githubusercontent.com/82112471/165862181-2c641fee-15bb-46d8-8e65-f43aa8d9546b.png)

# LSD Preview

Coming soon...

# Meth Preview

[https://streamable.com/0pcjlt](https://streamable.com/0pcjlt)

# Older qb-core

qb-core/shared/item.lua

```lua
    ["wet_weed"] 		 	 	 	 = {["name"] = "wet_weed", ["label"] = "Moist Weed", ["weight"] = 3000, ["type"] = "item", ["image"] = "wet_weed.png", ["unique"] = false, ["useable"] = false, ["shouldClose"] = false, ["combinable"] = nil, ["expire"] = 90, ["description"] = "Wet weed that needs to be treated!"},
    ["coke"] 		 	 	 	     = {["name"] = "coke", ["label"] = "Cocaine", ["weight"] = 1000, ["type"] = "item", ["image"] = "coke.png", ["unique"] = false, ["useable"] = false, ["shouldClose"] = false, ["combinable"] = nil, ["expire"] = 90, ["description"] = "Processed cocaine"},
    ["coca_leaf"] 		 	 	 	 = {["name"] = "coca_leaf", ["label"] = "Cocaine leaves", ["weight"] = 1500, ["type"] = "item", ["image"] = "coca_leaf.png", ["unique"] = false, ["useable"] = false, ["shouldClose"] = false, ["combinable"] = nil, ["expire"] = 90, ["description"] = "Cocaine leaves that must be processed!"},
    ["cannabis"] 			 		 = {["name"] = "cannabis", ["label"] = "Cannabis", ["weight"] = 2500, ["type"] = "item", ["image"] = "cannabis.png", ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["expire"] = 90, ["description"] = "Uncured cannabis"},
    ["marijuana"] 			 		 = {["name"] = "marijuana", ["label"] = "Marijuana", ["weight"] = 500, ["type"] = "item", ["image"] = "marijuana.png", ["unique"] = false, ["useable"] = false, ["shouldClose"] = true, ["combinable"] = nil, ["expire"] = 90, ["description"] = "Some fine smelling buds."},
    ["chemicals"] 		 	 	 	 = {["name"] = "chemicals", ["label"] = "Chemicals", ["weight"] = 1500, ["type"] = "item", ["image"] = "chemicals.png", ["unique"] = false, ["useable"] = false, ["shouldClose"] = false, ["combinable"] = nil, ["expire"] = 90, ["description"] = "Chemicals, handle with care..."},
    ["poppyresin"] 		 	 	 	 = {["name"] = "poppyresin", ["label"] = "Poppy resin", ["weight"] = 2000, ["type"] = "item", ["image"] = "poppyresin.png", ["unique"] = false, ["useable"] = false, ["shouldClose"] = false, ["combinable"] = nil, ["expire"] = 90, ["description"] = "It sticks to your fingers when you handle it."},
```

# New qb-core update

qb-core/shared/item.lua

```lua
    wet_weed 		 	 	 	 = {name = "wet_weed", label = "Moist Weed", weight = 3000, type = "item", image = "wet_weed.png", unique = false, useable = false, shouldClose = false, combinable = nil, expire = 90, description = "Wet weed that needs to be treated!"},
    coke 		 	 	 	     = {name = "coke", label = "Cocaine", weight = 1000, type = "item", image = "coke.png", unique = false, useable = false, shouldClose = false, combinable = nil, expire = 90, description = "Processed cocaine"},
    coca_leaf 		 	 	 	 = {name = "coca_leaf", label = "Cocaine leaves", weight = 1500, type = "item", image = "coca_leaf.png", unique = false, useable = false, shouldClose = false, combinable = nil, expire = 90, description = "Cocaine leaves that must be processed!"},
```

# Add icon images

qb-inventory > html > images

# Dependencies

* [PolyZone](https://github.com/mkafrin/PolyZone)
* [qb-target](https://github.com/BerkieBb/qb-target)
* [qb-menu](https://github.com/qbcore-framework/qb-menu)
* [ps-ui](https://github.com/Project-Sloth/ps-ui)
* [Meth Lab IPL](https://github.com/Bob74/bob74_ipl/tree/master/dlc_tuner)

