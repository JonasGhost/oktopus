<p align="center">
<img src="https://user-images.githubusercontent.com/83298718/220207485-8c2aac78-95eb-4b43-b23e-c4bfa6cd30e6.png"/>
</p>
<br/>
<ul>
    <li>
        <a href="https://github.com/leandrofars/oktopus/blob/main/README.pt-br.md">Readme em Português</a>
    </li>
</ul>
<ul>
    <li>
        <h4>Introduction:</h4>
    </li>
</ul>        
<p>
This repository aims to promote the development of a multi-vendor management platform for IoTs. Any device that follows the TR-369 protocol can be managed. The main objective is to facilitate and unify device management, which generates countless benefits for the end user and service providers, suppressing the demands that today's technologies require: device interconnection, data collection, speed, availability and much more. .
</p>
<ul>
    <li>
        <h4>TR-069 ---> TR-369 :</h4>
    </li>
</ul>  
<p>
The advent of the Internet of Things brings countless opportunities and challenges for service providers, with over a billion devices across the globe today making use of <a href="https://www.broadband-forum.org/download /TR-069_Amendment-2.pdf">TR-069</a>, what is the future of the protocol and what can we expect ahead?
</p>
<p>
The CWMP (CPE Wan Management Protocol), better known as TR-069, opened many doors for the ecosystem of providers, through which it is possible to deliver services with agility, which meet or exceed customer expectations, with proactive management and secure network, also bearing in mind the lower cost and greater efficiency for service providers.
</p>
<p>
With the rise of what we now call the smart home, the Internet of Things and the demand for increasingly interconnected and cloud-based environments, new demands and obstacles have emerged, opening the door to the creation of a new form of communication that meets the needs of current market needs.
</p>
<p>
There is a fierce race to monetize the IoT devices that are now part of the connected home and other environments. As a result, many companies are creating their own proprietary solutions; this is understandable given such pressure generated by the promise of Smart Home monetization. Unfortunately, these applications contribute to a poor ecosystem, where a provider ends up dependent and limited to a vertical solution, from a single vendor. This generates an <b>low competition environment (which leads to greater risks), less innovation, and the potential for very high cost solutions</b>.
</p>
<p>
The technologies behind Wi-Fi, device-to-device connectivity, the Smart Home and IoTs are constantly evolving and improving. It is important that when service providers look for a solution, they look for something that is "future proof", always thinking ahead.
</p>
<p>
Seeking to solve the challenges mentioned above, providers and manufacturers together developed the USP (User Services Platform), defined by the Broadband Forum's TR-369 standard, which is the natural evolution of the TR-069. <b>This new standard is designed to be flexible, secure, scalable and standardized to meet the demands of a connected world today, and in the future.</b>
</p>

<ul>
    <li>
        <h4>Companies/Institutions involved in the creation of the TR-369:</h4>
        <ul>
            <li> 
            Google
            </li>
            <li> 
            Nokia
            </li>
            <li> 
            Huawei
            </li>
            <li> 
            Axiros
            </li>
            <li> 
            Orange
            </li>
            <li> 
            Commscope
            </li>
            <li> 
            Assia
            </li>
            <li> 
            AT&AT
            </li>
            <li> 
            NEC
            </li>
            <li> 
            Arris
            </li>
            <li> 
            QA Cafe
            </li>
        </ul>
    </li>
</ul> 

--------------------------------------------------------------------------------------------------------------------------------------------------------

<ul>
    <li>
        <h4>Topology:</h4>
    </li>
</ul>  

<img src="https://usp.technology/specification/architecture/usp_architecture.png"/>

![image](https://github.com/leandrofars/oktopus/assets/83298718/b1d5a0c7-4567-464c-bc9b-1956ef5c5f3b)

![image](https://github.com/leandrofars/oktopus/assets/83298718/7b46dc1f-5eb2-4a1b-8e77-376b0836948a)

<ul>
    <li>
        <h4>Protocols:</h4> 
        
![image](https://github.com/leandrofars/oktopus/assets/83298718/9b789f0b-cb0c-4cec-8b8e-767ba21bffae)
    </li>
</ul>

<ul>
    <li>
        <h4>Notifications/Data collection:</h4> 
        You can create notifications that fire on a value change, object creation and removal, complete operation, or an event.
        
![image](https://github.com/leandrofars/oktopus/assets/83298718/184899a3-52e7-491a-8ee7-7b442fe50719)
    </li>
</ul>

<ul>
    <li>
        <h4><a href="https://github.com/BroadbandForum/obuspa">OB-USP-A</a> (Open Broadband User Services Platfrom Agent):</h4> 
        <ul>
             <li>
             Designed for embedded software (~400kb on ARM)
             </li>
             <li>
             Encoded in C
             </li>
             <li>
             License <a href="https://opensource.org/license/bsd-3-clause/">BSD 3-Clause</a>
             </li>
             <li>
             Made for Linux environments
             </li>
        </ul>
    </li>
</ul>

<ul>
    <li>
        <h4>Data Analysis</h4>
The protocol has a mechanism called "Bulk Data", where it is possible to collect large volumes of data from the device, the data can be collected by HTTP, or another telemetry MTP defined in the TR standard, this data can be in JSON, CSV format or XML. This generates the opportunity to use AI on top of this data, obtaining relevant information that can be used for different purposes, from predicting events, KPIs, information for the commercial area, but also for the best configuration of a device.
    </li>
</ul>

<ul>
    <li>
        <h4>WiFi:</h4>
It has over 130 Wi-Fi configuration and diagnostics metrics, many of these settings and parameters are a trade-off between signal coverage area, latency and throughput. When deploying Wi-Fi systems, there is a tendency to maintain the same configuration on all clients, causing the technology to perform below expectations. Machine Learning combined with the data analysis mentioned in the previous topic makes it possible to automate the management and optimization of Wireless networks, where a big data approach is able to find the ideal configuration for each device.
        
![image](https://github.com/leandrofars/oktopus/assets/83298718/3d6fe3e8-3ca2-460b-9583-da89b42753f8)
    </li>
</ul>

<ul>
    <li>
       <h4>Commands:</h4>
         It is possible to perform commands remotely on the product, such as: firmware update, reboot, reset, search for neighboring networks, backup, ping, network diagnostics and many others.
    </li>
</ul>

<ul>
    <li>
        <h4>IoT:</h4>
<div align="center">
<img src="https://github.com/leandrofars/oktopus/assets/83298718/a2a12d9d-05a0-428b-ba3f-1ad83c876301" width="90%"/>
<br/>
<img src="https://github.com/leandrofars/oktopus/assets/83298718/91a87f43-3de7-42bd-a689-a4e14eecf5c0" width="60%"/>
<br/>
<img src="https://github.com/leandrofars/oktopus/assets/83298718/73e2e360-d53e-494e-9a50-60c83dae75df" width="60%"/>
<div>
    </li>
</ul>

<ul>
    <li>
<h4>Software Modules:</h4>
Currently, telecommunications giants and startups, publishing new software daily, slow delivery cycles and manual and time-consuming quality assurance processes make it difficult for integrators and service providers to compete. USP "Software Module Management" allows a containerized approach to the development of software for embedded devices, making it possible to drastically reduce the chance of error in software updates, it also facilitates the integration of third parties in a device, still keeping the firmware part isolated from Vendor.
<br/>
<img src="https://github.com/leandrofars/oktopus/assets/83298718/64664b0e-81cd-4a29-bbc5-b4186a04dfa2" width="50%"/>
    </li>
</ul>



--------------------------------------------------------------------------------------------------------------------------------------------------------

<ul><li><h4>Infrastructure:</h4></li></ul>

![image](https://github.com/leandrofars/oktopus/assets/83298718/a93df5aa-31fd-486f-8af1-7911f552fea1)

<ul>
    <li>
        <h4>API:</h4>
        <ul>
            <li> 
            <a href="https://documenter.getpostman.com/view/18932104/2s93eR3vQY#10c46751-ede9-4ea1-8ea4-264ebf539e5e">Documentation </a>
            </li>
            <li> 
            <a href="https://www.postman.com/docking-module-astronomer-46169629/workspace/oktopus">Workspace of tests and development</a>
            </li>
        </ul>
    </li>
</ul>
<ul>
    <li>
        <h4>Developer:</h4>
Run app using Docker:
<pre>
leandro@leandro-laptop:~$ cd oktopus/devops
leandro@leandro-laptop:~/oktopus/devops$ docker compose up
</pre>
    </li>
    <li>
Basic manual compilation and run:
    <ul>
        <li>
        <b>Dependencies:</b> Node version: v14.20.0 | Go version: v1.18.1
        </li>
        <li>
        Mqtt broker:
            <pre>leandro@leandro-laptop:~$ cd oktopus/backend/services/mochi/ && go run cmd/main.go -redis "127.0.0.1:6379"</pre>
        </li>
        <li>
        TR-369 controller:
            <pre>
leandro@leandro-laptop:~$ cd oktopus/backend/services/controller/ && go run cmd/oktopus/main.go -u root -P root -mongo "mongodb://127.0.0.1:27017"</pre>
        </li>
        <li>
        Socketio server:
            <pre>
leandro@leandro-laptop:~$ cd oktopus/backend/services/socketio && npm i && npm start</pre>
        </li>
        <li>
        Frontend:
            <pre>
leandro@leandro-laptop:~$ cd oktopus/frontend && npm i && npm run dev</pre>
        </li>       
    </ul>
OBS: Do not use those instructions in production. To implement the project in production you might use more resources that are already avaiable in Oktopus, but would take longer to explain in this README. Soon, there will be more help and explanations about those extra needed configs. 
</li>
    <li>
Device test agent config:
    </li>
<ul>
        <li>
<b>Device.LocalAgent.</b>
<pre>
"CertificateNumberOfEntries": "0",
"Controller.1.Alias": "",
"Controller.1.AssignedRole": "",
"Controller.1.BootParameterNumberOfEntries": "0",
"Controller.1.ControllerCode": "",
"Controller.1.Enable": "true",
"Controller.1.EndpointID": "oktopusController",
"Controller.1.InheritedRole": "Device.LocalAgent.ControllerTrust.Role.1",
"Controller.1.MTP.1.Alias": "",
"Controller.1.MTP.1.Enable": "true",
"Controller.1.MTP.1.MQTT.Reference": "Device.MQTT.Client.1",
"Controller.1.MTP.1.MQTT.Topic": "oktopus/v1/controller",
"Controller.1.MTP.1.Protocol": "MQTT",
"Controller.1.MTPNumberOfEntries": "1",
"Controller.1.PeriodicNotifInterval": "15",
"Controller.1.PeriodicNotifTime": "0001-01-01T00:00:00Z",
"Controller.1.ProvisioningCode": "",
"Controller.1.USPNotifRetryIntervalMultiplier": "2000",
"Controller.1.USPNotifRetryMinimumWaitInterval": "5",
"ControllerNumberOfEntries": "1",
"ControllerTrust.ChallengeNumberOfEntries": "0",
"ControllerTrust.CredentialNumberOfEntries": "0",
"ControllerTrust.Role.1.Alias": "cpe-1",
"ControllerTrust.Role.1.Enable": "true",
"ControllerTrust.Role.1.Name": "Full Access",
"ControllerTrust.Role.1.Permission.1.Alias": "cpe-1",
"ControllerTrust.Role.1.Permission.1.CommandEvent": "r-xn",
"ControllerTrust.Role.1.Permission.1.Enable": "true",
"ControllerTrust.Role.1.Permission.1.InstantiatedObj": "rw-n",
"ControllerTrust.Role.1.Permission.1.Obj": "rw-n",
"ControllerTrust.Role.1.Permission.1.Order": "0",
"ControllerTrust.Role.1.Permission.1.Param": "rw-n",
"ControllerTrust.Role.1.Permission.1.Targets": "Device.",
"ControllerTrust.Role.1.PermissionNumberOfEntries": "1",
"ControllerTrust.RoleNumberOfEntries": "2",
"EndpointID": "os::4851CF-000000000002",
"MTP.1.Alias": "",
"MTP.1.Enable": "false",
"MTP.1.MQTT.PublishQoS": "0",
"MTP.1.MQTT.Reference": "Device.MQTT.Client.1",
"MTP.1.MQTT.ResponseTopicConfigured": "oktopus/v1/controller",
"MTP.1.MQTT.ResponseTopicDiscovered": "oktopus/v1/agent/os::4851CF-000000000002",
"MTP.1.Protocol": "MQTT",
"MTP.1.Status": "Down",
"MTPNumberOfEntries": "1",
"RequestNumberOfEntries": "0",
"SoftwareVersion": "5.0.0",
"SubscriptionNumberOfEntries": "0",
"SupportedFingerprintAlgorithms": "SHA-1, SHA-224, SHA-256, SHA-384, SHA-512",
"SupportedProtocols": "STOMP, CoAP, MQTT, WebSocket",
"UpTime": "42"
</pre>
    </li>
    <li>
<b>Device.MQTT.Client.1</b>
    </li>
    <pre>
"Alias": "cpe-1",
"BrokerAddress": "10.100.250.4",
"BrokerPort": "1883",
"CleanSession": "false",
"CleanStart": "false",
"ClientID": "",
"ConnectRetryIntervalMultiplier": "2000",
"ConnectRetryMaxInterval": "30720",
"ConnectRetryTime": "5",
"Enable": "true",
"KeepAliveTime": "30",
"Name": "",
"Password": "",
"ProtocolVersion": "5.0",
"RequestProblemInfo": "false",
"RequestResponseInfo": "false",
"ResponseInformation": "oktopus/v1/agent/os::4851CF-000000000002",
"Status": "Connected",
"Subscription.1.Alias": "cpe-1",
"Subscription.1.Enable": "false",
"Subscription.1.QoS": "1",
"Subscription.1.Topic": "oktopus/v1/agent",
"SubscriptionNumberOfEntries": "1",
"TransportProtocol": "TCP/IP",
"Username": "test"</pre>
</ul>
</ul>

--------------------------------------------------------------------------------------------------------------------------------------------------------

<p>Are you going to use our project in your company? would like to talk about TR-369 and IoT management, we're online on <a href="https://join.slack.com/t/oktopustr-369/shared_invite/zt-1znmrbr52-3AXgOlSeQTPQW8_Qhn3C4g">Slack</a>.</p>
<p>If you are interested in internal information about the team and our intentions, visit our <a href="https://github.com/leandrofars/oktopus/wiki">Wiki</a>.</p>

--------------------------------------------------------------------------------------------------------------------------------------------------------

<p>Bibliographic sources: <a href="https://www.broadband-forum.org/download/MU-461.pdf">MU-461.pdf</a>, <a href="https:/ /usp.technology/specification/index.htm">TR-369.html</a>, <a href="https://drive.google.com/drive/folders/1N7FqK0PkDhjCN5s3OhQ_wmz9UcTSwRCX">USP Training Session Slides</usp.technology/specification/index.htm">TR-369.html</a></p>
