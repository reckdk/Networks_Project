# Networks_Project
CSE534-Fundamentals of Computer Networks-Project

1. Download ISCX-2012 Dataset from

   https://www.unb.ca/cic/datasets/ids.html

2. Extract data and make file structure as below:

```
.
├── Extract_Data.ipynb
├── ISCX_CNN.ipynb
├── ISCX_CNN-LightModel.ipynb
├── labeled_flows_xml
│   ├── labeled_flows_xml.zip
│   ├── readme.txt
│   ├── TestbedMonJun14Flows.xml
│   ├── TestbedMonJun14Flows.xsd
│   ├── TestbedSatJun12Flows.xml
│   ├── TestbedSatJun12Flows.xsd
│   ├── TestbedSunJun13Flows.xml
│   ├── TestbedSunJun13Flows.xsd
│   ├── TestbedThuJun17-1Flows.xml
│   ├── TestbedThuJun17-1Flows.xsd
│   ├── TestbedThuJun17-2Flows.xml
│   ├── TestbedThuJun17-2Flows.xsd
│   ├── TestbedThuJun17-3Flows.xml
│   ├── TestbedThuJun17-3Flows.xsd
│   ├── TestbedTueJun15-1Flows.xml
│   ├── TestbedTueJun15-1Flows.xsd
│   ├── TestbedTueJun15-2Flows.xml
│   ├── TestbedTueJun15-2Flows.xsd
│   ├── TestbedTueJun15-3Flows.xml
│   ├── TestbedTueJun15-3Flows.xsd
│   ├── TestbedWedJun16-1Flows.xml
│   ├── TestbedWedJun16-1Flows.xsd
│   ├── TestbedWedJun16-2Flows.xml
│   ├── TestbedWedJun16-2Flows.xsd
│   ├── TestbedWedJun16-3Flows.xml
│   └── TestbedWedJun16-3Flows.xsd
├── testbed-11jun.pcap
└── testbed-12jun.pcap
```

3. Run `Extract_Data.ipynb`  to produce  `Database2 ` for cached data.

```
.
├── Database2
│   ├── destinationPayload_TestbedMonJun14Flows.xml.npy
│   ├── destinationPayload_TestbedSatJun12Flows.xml.npy
│   ├── destinationPayload_TestbedSunJun13Flows.xml.npy
│   ├── destinationPayload_TestbedThuJun17-2Flows.xml.npy
│   ├── destinationPayload_TestbedThuJun17-3Flows.xml.npy
│   ├── destinationPayload_TestbedTueJun15-1Flows.xml.npy
│   ├── destinationPayload_TestbedTueJun15-2Flows.xml.npy
│   ├── destinationPayload_TestbedTueJun15-3Flows.xml.npy
│   ├── destinationPayload_TestbedWedJun16-1Flows.xml.npy
│   ├── destinationPayload_TestbedWedJun16-2Flows.xml.npy
│   └── destinationPayload_TestbedWedJun16-3Flows.xml.npy
```

4. Run `ISCX_CNN.ipynb` and `ISCX_CNN-LightModel.ipynb` to train and validate model for **Intrusion Detection**.