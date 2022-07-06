# free5gc-helm
## Description
Helm chart for free5GC v3.0.5
NOTICE: This helm chart exclude MongoDB and UPF currently.

## Usage
1. Apply MongoDB statefulset
2. Apply UPF
3. Apply configmap
4. install Helm Chart

## Known issue
The helm chart only create several resource (Webconsole deployment, free5gc-udr service)

## TODO
- [] Fix: some deployment values missing
- [] Add: Merge corresponding configmap into Helm chart.
- [] Add: MongoDB statefulset template
- [] Add: Upf deployment template
- [] Add: free5gc v3.1.1 Helm chart
