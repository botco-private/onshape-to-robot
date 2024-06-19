# OnShape to Robot (SDF/URDF)

<p align="center">
<img src="docs/source/_static/img/main.png" />
</p>

This tool is based on the [OnShape API](https://dev-portal.onshape.com/) to retrieve
informations from an assembly and build an SDF or URDF model suitable for physics
simulation.

* [Documentation](https://onshape-to-robot.readthedocs.io/)
* [Examples](https://github.com/rhoban/onshape-to-robot-examples)

To run from BotCo fork - 
```
python -m onshape_to_robot.onshape_to_robot.py <path containing config.json>
```
Example:
```
python -m onshape_to_robot.onshape_to_robot.py /home/paril/Documents/src/autonomy/firmware/config/urdfs/beta-bot
```