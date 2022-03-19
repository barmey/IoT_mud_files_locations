# IoT_mud_files_locations
 We generate MUD files from captures of 31 IoT devices (plugs, cameras, bulbs), activities at 14 countries, using MUDGEE. The resulted MUD files (per countries) are available at the repo.
![image](https://user-images.githubusercontent.com/21200923/137639821-792a64a9-e89c-4105-9d6e-b78263def041.png)

## Citation

If you find this data useful in your research, please cite our papers:

```
@INPROCEEDINGS{220669,
AUTHOR=”Anat Bremler-Barr and Bar Meyuhas and Ran Shister”,
TITLE=”One MUD to Rule Them All: IoT Location Impact”,
BOOKTITLE=”NOMS 2022 – Full and short papers () “,
ADDRESS=””,
DAYS=”25-29″,
MONTH=”apr”,
YEAR=”2022″,
ABSTRACT=”Analyzing the network behavior of IoT devices, including which domains, protocols, and ports the device communicates with, is a fundamental challenge for IoT security and identification. Solutions that analyze and manage these areas must be able to learn what constitutes normal device behavior and then extract rules and features to permit only legitimate behavior or identify the device. The Manufacturer Usage Description (MUD) is an IETF white-list protection scheme that formalizes the authorized network behavior in a MUD file; this MUD file can then be used as a type of firewall mechanism. We demonstrate that learning what is normal behavior for an IoT device is more challenging than expected. In many cases, the same IoT device, with the same firmware, can exhibit different behavior or connect to different domains with different protocols, depending on the device’s geographical location. We analyze and explain use-cases in which the location impacts device behavior. Then, we present a technique to generalize MUD files. By processing MUD files that originate in different locations, we can generalize and create a comprehensive MUD file that is applicable for all locations. To conduct the research, we created MUDIS, a MUD Inspection System tool, that compares and generalizes MUD files. Our open-source MUDIS tool and dataset are available online to researchers and IoT manufacturers, allowing anyone to visualize, compare, and generalize MUD files.”,
KEYWORDS=””,
URL=”http://XXXXX/220669.pdf”
}
```
