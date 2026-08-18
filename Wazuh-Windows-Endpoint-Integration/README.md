# Wazuh Windows Endpoint Integration

## Objective

Integrate a Windows endpoint with Wazuh and verify that Windows telemetry is successfully collected by the Wazuh Agent and received by the Wazuh Manager.

## Lab Environment

| Component | Details |
|---|---|
| Windows Endpoint | KAMRAN-PC |
| Windows IP | 192.168.23.131 |
| Domain | Kamran.local |
| Domain Controller | 192.168.23.128 |
| Wazuh Manager | 192.168.23.133 |
| Wazuh Agent | KamranAgent |
| Agent ID | 001 |

## Work Completed

- Verified Wazuh Agent status.
- Verified Windows Wazuh service.
- Tested connectivity between the Windows endpoint and Wazuh Manager.
- Verified the domain secure channel.
- Verified Wazuh Agent logs.
- Generated a controlled Windows event.
- Verified the event in Wazuh archives.
- Verified the event in Wazuh Discover.
- Verified Filebeat output connectivity.

## Evidence

### 1. Wazuh Agent Status

![Wazuh Agent Status](screenshots/01-agent-status.png)

### 2. Windows Wazuh Service

![Windows Wazuh Service](screenshots/02-windows-wazuh-service.png)

### 3. Agent Manager Connectivity

![Agent Manager Connectivity](screenshots/03-agent-manager-connectivity.png)

### 4. Domain Secure Channel

![Domain Secure Channel](screenshots/04-domain-secure-channel.png)

### 5. Wazuh Agent Log

(./<img width="570" height="119" alt="05-wazuh-agent-log-collection" src="https://github.com/user-attachments/assets/39d95c77-4288-4974-bce1-5441f774f889" />
)

### 6. Test Event Created

![Test Event Created](screenshots/06-test-event-created.png)

### 7. Wazuh Archive Event

![Wazuh Archive Event](screenshots/07-wazuh-archive-event.png)

### 8. Wazuh Discover Event

![Wazuh Discover Event](screenshots/08-wazuh-discover-event.png)

### 9. Filebeat Output

![Filebeat Output](screenshots/09-filebeat-output.png)

## Result

The Windows endpoint was successfully integrated with the Wazuh environment.

The lab verified the endpoint's Wazuh service, network connectivity, domain secure channel, agent logging, Windows event generation, Wazuh archive ingestion, Wazuh Discover visibility, and Filebeat output connectivity.
