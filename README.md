# D&D Development - Enhanced ESX Framework Recipe

## Overview
This is the official recipe for D&D Development's Enhanced ESX Framework server base. Created by Darknest_4, updated on 2025.05.10.

## Features
- Enhanced ESX Legacy base setup with extended functionalities
- Pre-configured with Overextended resources (ox_inventory, ox_lib, etc.)
- Multiple notification systems (dnd-notify, mythic_notify)
- Multiple progress bar systems (progressbar, mythic_progbar)
- Full job system with vehicle shop, mechanic, taxi and more
- Skinchanger and esx_skin kept for maximum compatibility
- Advanced phone system (npwd)
- Hungarian language support
- Well-organized server.cfg with optimized resource loading order
- Pre-configured with txAdmin template variables

## Resources Included

### Core Resources
- ESX Core
- skinchanger (kept for compatibility)
- esx_skin (kept for compatibility)
- bob74_ipl (Map improvements)
- pma-voice
- illenium-appearance (alternative to esx_skin)

### Overextended Resources
- ox_lib
- ox_inventory
- ox_doorlock
- ox_target
- ox_mysql
- ox_core
- ox_police

### ESX Jobs and Addons
- esx_ambulancejob (Emergency Medical Services)
- esx_policejob (Law Enforcement)
- esx_vehicleshop (Vehicle dealership)
- esx_mechanicjob (Vehicle repair service)
- esx_taxijob (Taxi service)
- esx_barbershop (Character customization)
- esx_clotheshop (Clothing stores)
- esx_garage (Vehicle storage)
- esx_weaponshop (Weapon stores)
- esx_jobs (Various legal jobs)
- esx_shops (Various shops)
- esx_banking (Banking system)

### Advanced Scripts and UI
- dnd-notify (Custom notification system)
- mythic_notify (Alternative notification system)
- progressbar (Clean progress bar)
- mythic_progbar (Alternative progress bar)
- npwd (Advanced phone system)
- sqib-scripts (Utility scripts)
- GTAO chat theme (Modern stylish chat interface)

## Installation

### Method 1: Using txAdmin (Recommended)
1. Start a new server with txAdmin
2. Choose "Remote Template" when prompted
3. Enter the following URL:
   ```
   https://raw.githubusercontent.com/Darknest-4/recipe/main/recipes.yaml
   ```
4. Follow the on-screen instructions to complete the installation
5. All resources will be automatically downloaded and configured

### Method 2: Manual Installation
1. Clone or download this repository
2. Follow the tasks in the recipes.yaml file manually
3. Set up your database with the es_extended name

## Configuration
- Database name: es_extended
- Default server name: D&D Development
- Default server port: 30120
- Default language: Hungarian (hu-HU)

## Customization
- The recipe uses txAdmin template variables for easy customization
- The server.cfg will be automatically configured during deployment
- Add your Steam API key and license key
- Modify the admin identifier in server.cfg

## Credits
- Created by: Darknest_4
- Enhanced by: Darknest_4 on 2025.05.10
- ESX Framework: [ESX-Framework](https://github.com/esx-framework)
- Overextended: [Overextended](https://github.com/overextended)
- Project Error (NPWD): [Project Error](https://github.com/project-error)
- QBCore Framework (Progressbar): [QBCore](https://github.com/qbcore-framework)
- Mythic Scripts: [Mythic](https://github.com/mythicrp)

## License
This project is licensed under the MIT License.
