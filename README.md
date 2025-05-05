# D&D Development - ESX Framework Recipe

## Overview
This is the official recipe for D&D Development's ESX Framework server base. Created by Darknest_4 on 2025.05.05.

## Features
- Complete ESX Legacy base setup
- Pre-configured with Overextended resources (ox_inventory, ox_lib, etc.)
- Custom notification system (dnd-notify)
- Hungarian language support
- Removed unnecessary ESX resources
- Pre-configured server.cfg with txAdmin template variables

## Resources Included

### Core Resources
- ESX Core
- bob74_ipl (Map improvements)
- pma-voice
- illenium-appearance (replacement for esx_skin)

### Overextended Resources
- ox_lib
- ox_inventory
- ox_doorlock
- ox_target
- ox_mysql
- ox_police (replaces esx_policejob)

### Additional Resources
- dnd-notify (custom notification system)
- esx_ambulancejob (Emergency Medical Services)
- esx_policejob (Law Enforcement)
- esx_chat with GTAO theme (Stylish chat interface)

## Installation

### Method 1: Using txAdmin
1. Start a new server with txAdmin
2. Choose "Remote Template" when prompted
3. Enter the following URL:
   ```
   https://raw.githubusercontent.com/Darknest-4/recipe/main/recipes.yaml
   ```
4. Follow the on-screen instructions to complete the installation

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
- ESX Framework: [ESX-Framework](https://github.com/esx-framework)
- Overextended: [Overextended](https://github.com/overextended)

## License
This project is licensed under the MIT License.
