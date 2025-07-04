# Lightwheel-simready-asset
Open-source 3D digital assets for simulation and robot training. Free for non-commercial use.


Lightwheel Simready Assets
<div align="center">
Show Image
Show Image
Show Image

Show Image

Open-source USD assets for Isaac Sim robotics simulation

🚀 Download Assets • 💬 Discord Community • 📧 Contact

</div>
Overview
259 high-quality USD assets specifically designed for NVIDIA Isaac Sim robotics simulation and training.

251 Manipulation Assets - Objects for robot manipulation training
8 Locomotion Assets - Environments for robot navigation training
USD Format - Native .usd/.usdz files ready for Isaac Sim
Fully Tested - Validated with Isaac Lab, teleoperation, and RL workflows
Quick Start
bash
# 1. Visit our asset library
https://www.lightwheel.ai/assets-list

# 2. Download USD assets
# 3. Drag and drop into Isaac Sim
# 4. Use Shift + Left Click for articulated objects (doors, drawers)
Attribution Required: Use naming format lightwheel_{asset_name} in your projects

Asset Categories
<table> <tr> <td>
🦾 Manipulation (251 Assets)
Household objects
Kitchen items & tools
Industrial components
Interactive elements (doors, drawers, cabinets)
Training objects & geometric shapes
</td> <td>
🚶 Locomotion (8 Assets)
Terrain variations
Navigation environments
Obstacle courses
Stairs & slopes
Indoor/outdoor spaces
</td> </tr> </table>
Technical Specifications
Feature	Details
Format	USD (.usd, .usdz)
Target Platform	NVIDIA Isaac Sim 2023.1.1+
Physics	PhysX-ready collision meshes
Rendering	RTX-optimized PBR materials
Interaction	Pre-configured articulation
Testing	Isaac Lab, Teleoperation, RL validated
Usage Examples
Basic Import
python
# Isaac Sim Python API example
from omni.isaac.core.utils.stage import add_reference_to_stage

# Import asset
add_reference_to_stage(
    usd_path="/path/to/lightwheel_kitchen_table.usd",
    prim_path="/World/KitchenTable"
)
Attribution in Code
python
# Required attribution in your project
asset_name = "lightwheel_kitchen_table"  # ✅ Correct
asset_name = "kitchen_table"            # ❌ Missing attribution
Interaction Controls
Action	Control
Articulated Objects	Shift + Left Mouse Button
Object Selection	Left Mouse Button
Camera Movement	Middle Mouse + Drag
Works with doors, drawers, cabinets, and other moving parts

License & Attribution
Apache License 2.0
✅ Commercial use allowed
✅ Modification allowed
✅ Distribution allowed
✅ Private use allowed
Required Attribution
Use the naming convention: lightwheel_{asset_name}

Examples:

lightwheel_kitchen_table
lightwheel_robot_arm
lightwheel_office_chair
Community & Support
<table> <tr> <td align="center">
💬 Discord
Real-time Support

Show Image

</td> <td align="center">
👥 Product Team
Yaqi Luo

Show Image

</td> <td align="center">
🔧 Technical Team
Frank Chen

Show Image

</td> </tr> </table>
Reporting Issues
Found a faulty asset? Report it here:

Method	Best For	Response Time
💬 Discord	Quick questions	Fastest
📧 Email	Detailed reports	24-48 hours
🐛 GitHub Issues	Bug tracking	Community visibility
Include in your report:

Asset name and download link
Isaac Sim version
Issue description
Steps to reproduce
Why Choose Lightwheel Assets?
<div align="center">
✨ Isaac Sim Native	🔧 Plug & Play	✅ Battle-Tested
USD format designed for Isaac Sim	No conversion needed	Validated with Isaac Lab & RL
🎯 Interactive	🆓 Free & Open	🤝 Community
Pre-configured articulation	Apache 2.0 license	Active Discord support
</div>
Contributing
We welcome contributions! Here's how to help:

🐛 Bug Reports → Open an issue
💡 Feature Requests → Discord
🔧 Asset Improvements → Submit a PR
📚 Documentation → Help improve guides
Contact Information
Lightwheel AI
📍 10080 N Wolfe Rd SW3 200, Cupertino, CA 95014
📧 haibo.yang@lightwheel.ai
🌐 https://www.lightwheel.ai

<div align="center">
Made with ❤️ by the Lightwheel AI team

Show Image
Show Image
Show Image

isaacssim usd robotics simulation 3d-assets machine-learning robot-training manipulation locomotion open-source apache-license nvidia omniverse

</div>

