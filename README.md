
# PBRP Action Builder

!!Under Construction!!
Builds PBRP with github workflow.



## How To Use

- Fork this repository
-  Go to `Action` tab > `All workflows` > `Recovery - Build` > `Run workflow`, then fill all the        required information
* Manifest Url (PBRP Minimal Manifest URL)
* Manifest Branch (android-12.1,twrp-12.1)
* Device Tree (Your device tree repository link)
* Device Tree Branch (Your device tree repository branch)
* Device Name (Your device codename)
* Device Path (device/brand/codename)
* Build Target (boot, recovery, vendorboot)
## Features

-  Initially, it only have two default choices for manifest branch branch: android-12.1, twrp-12.1. If there's more to it, feel free to modify the .yml configurations.
- Can Build PBRP Recovery with github action


## Credits
- https://github.com/carlodandan/OrangeFox-Action-Builder for the wonderful git repo
