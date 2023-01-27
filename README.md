# **Mine-X-Farm-Regen**
Regenerate All Ores , Ore Blocks And Wood With Custom Delay , Drop , Regions

## **INFORMATION**
Mine X Farm Regen Allows You To Easily Set Up Areas Where Blocks Regenerate After Being Broken.   
You Have Complete Control Over What Blocks To Regen And Their Delays.  
This Plugin Needs No Dependencies And Is Verified To Work On 1.12-1.19. 
  
## **DOWNLOAD**
Current Version ➡️ ``Mine Farm Regen 3.0``   
Spigot ➡️ [Download](https://www.spigotmc.org/resources/mine-x-farm-regen%E2%9B%8F%EF%B8%8F-1-12-1-19.107060/)
  

## **INSTALLATION**
Download The Plugin And Upload It To The Plugins Folder And Restart Your Server  
This Plugin Will Only Work On Versions 1.12 -> 1.19.3 
   

## **REGIONS**
Regions Are Cuboidal Boxes Which Are Created Between Selected Pos1 and Pos2  
Only The Blocks Inside These Cuboidal Boxes Will Be Regenerated.  

### **Creating A Region**.  
**Method 1**
Using Regen Wand
+ Run Command ``/regen wand`` To Get Stone Axe Named Regen Wand 
+ Left Click A Block To Set Co-ordinates Of The Block As Pos1
+ Right Click A Block To Set Co-ordinates Of The Block As Pos2
+ Run Command ``/regen create (1-9)`` To Create A Region  
      
**Method 2**
Using Regen Commad
+ Run Command ``/regen pos1`` To Make Player Co-ordinates As Pos1
+ Run Command ``/regen pos2`` To Make Player Co-ordinates As Pos2
+ Run Command ``/regen create (1-9)`` To Create A Region

**Method 3**
Using Regen GUI
+ Run Command ``/regen pos1`` To Make Player Co-ordinates As Pos1
+ Run Command ``/regen pos2`` To Make Player Co-ordinates As Pos2
+ Run Command ``/regen GUI`` To Open Regen GUI
+ Click On ``Create Regen`` To Open Regen Create GUI
+ Click On The Region Number You Want Your Region Created

### **Deleting A Region**.  
**Method 1**
+ Run Command ``/regen delete (1-9)`` To Delete Region

**Method 2**
+ Run Command ``/regen GUI`` To Open Regen GUI
+ Click On ``Delete Regen`` To Open Regen Delete GUI
+ Click On The Region Number You Want Your Region Deleted

### **Supported Blocks**
+ Ores
 Coal Ore, Iron Ore, Gold Ore, Diamond Ore, Redstone Ore, Lapis Lazuli Ore, Emerald Ore, Deepslate Coal Ore, Deepslate Iron Ore, Deepslate Gold Ore, Deepslate Diamond Ore, Deepslate Redstone Ore, Deepslate Lapis Lazuli Ore, Deepslate Emerald Ore , Ancient Debris and Nether Quartz Ore.
+ Blocks
 Coal Block, Iron Block, Gold Block, Diamond Block, Redstone Block, Lapis Block, Emerald Block, Netherite Block , Stone, Deepslate.
+ Woods
 oak, spruce, birch, jungle, acacia, dark oak.

## Editing The Config File
``Block_Regen: true`` Regeneration On / OFF  
``Farm_Protect: true`` Protection Of Crop Damage By Player Or Entity By Jumping On / OFF  
  
``World: world`` Name Of Your World You Want Blocks To Regenerate  
``prefix: §f[§eRegen§f]`` The Prefix In Chat Messages. Use ``§`` For Colour Coding  

``Block_Name:`` Name Of The Supported Blocks To Regenerate  
    ``Amount: 1`` Number of Drops  
    ``Delay: 20`` Delay Of Regeneration In Seconds






