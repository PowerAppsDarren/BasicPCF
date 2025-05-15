# BasicPCF
As basic as it gets

```
# Notes to walk you through all this
# https://workflowy.com/s/practical-walkthroug/9TjQngDeg46GK4Ul
#
# Create this file for your workspace
vscode.code-workspace

pac pcf init --namespace YOUR_NAMESPACE_HERE --name YOUR_PCF_COMPONENT_NAME --template field
#pac pcf init --namespace SuperPowerLabs --name BasicPCF --template field
# Another Example
# pac pcf init --namespace PCTroubleShooter --name basicPCF --template field

npm install

# Add this to the top of index.tx - line 4, right after the class definition
private _container: HTMLDivElement;
# And add this to the init function
this._container = container;
const helloDiv = document.createElement("div");
helloDiv.innerText = "Hello, World!";
this._container.appendChild(helloDiv);

# Time to run and play
npm run build
npm start
```





