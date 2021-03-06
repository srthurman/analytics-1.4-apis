# report\_suite\_event

Data structure that contains information about a report suite's Events.

|Element|Type|Description|
|-------|----|-----------|
|**rsid** |`xsd:string` | The report suite ID. |
|**site\_title** |`xsd:string` | The report suite friendly name. |
|**ecommerce\_level** |`xsd:int` | The level of commerce support. Supported values include: `0`: Commerce support disabled. `50`: Commerce support enabled with no shopping cart. `52`: Commerce support fully enabled \(most common\). |
|**events** |[events](r_events.md#) | A list of `event` objects associated with this report suite. |

**Parent topic:** [Data Types](../data_types/c_datatypes.md)

