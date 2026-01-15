# Garry's Mod Developpement Kit Source Provider (GMDKS-P)
GMDKS-P is a framework designed to streamline and strengthen Garry’s Mod development by providing a unified, modular, and powerful structure for developers.

## Features

### 🎨 Color
- Shared color system across addons and gamemodes  
- Centralized storage using a hash vector  
- Thread-safe automatic color injection

### 🧩 Object
- Java-like object system with:
  - Dependency injection  
  - Strong encapsulation  
  - Exception handling (`throw`)  
  - Static
  - Class inheritance (`extend`)  
  - Interface implementation (`implement`)  
  - Abstract methods and `override` implementation
  - Override via metamethods without manual meta-object management  
  - + kill method in bonus
- Internal ORM-style mapping  
  - Optional Integrates with GraphQL service (see **GMDKS-M**)

### 📡 NetworkHandler
- Object-based networking with:
  - Internal buffered rate control  
  - No need for manual write-type specification  
  - Built-in cooldown and security layer

### 🧪 Test
- Integrated test framework:
  - Mock server  
  - Mock client

### 🔍 Fetch
- Retrieve data from another realm  
  without leaving the current execution context realm


# setup
```bash
cd GarrysMod/garrysmod/lua/includes
mkdir -p gdk && cd gdk
git clone https://github.com/Finnwinch/GMDKS-P.git
mv gdk/init.lua init.lua
echo "You can now use the GDKS table anywhere."
```

## Need support or want to contribute?

Join our [Discord](https://discord.gg/3khaVFTpRc)
