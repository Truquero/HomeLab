# Setup Defender

We are doing to install wazuh in the machine of the defender to analyze and visualize the data.

The defender is going to have the wazuh indexer,server and dashboard. In order to install this requirements follow the next steps

Enter the next code:

```
curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh && sudo bash ./wazuh-install.sh -a
```