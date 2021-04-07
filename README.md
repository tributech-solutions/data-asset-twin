# Tributech DataSpace Kit - Data Asset Twins

The DataSpace Kit (DSK) follows the approach to describes all entities of the system and relations between them using well known standards.

The supported standards are:
- [Digital Twins Definition Language (DTDL) Version 2](https://github.com/Azure/opendigitaltwins-dtdl/blob/master/DTDL/v2/dtdlv2.md)
- [Web of Things (WoT)](https://www.w3.org/TR/wot-thing-description/)

The definitions can be found in the corresponding sub-folders [DTDL](./DTDL) and [WoT](./WoT).

The DTDL-models are in widespread use by services of the DSK. The DSK exposes various services- and provides additional tooling to work with the given definitions.

Tools which are not part of a DSK ecosystem which can be used with the DTDL-definitions are:
- [VSCode extension](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-dtdl)
- [Azure Digital Twins (ADT)](https://azure.microsoft.com/en-us/services/digital-twins/)
- [Azure Digital Twins (ADT) explorer](https://github.com/Azure-Samples/digital-twins-explorer)

REMARK: The DTDL-definitions are maintained by Tributech. The WoT-definitions should be seen experimental and are currently not actively maintained.