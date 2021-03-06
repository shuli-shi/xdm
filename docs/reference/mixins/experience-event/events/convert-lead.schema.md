
# Convert Lead Schema

```
https://ns.adobe.com/xdm/mixins/events/convert-lead
```

Use for information regarding lead operation convert lead events.

| [Abstract](../../../../abstract.md) | [Extensible](../../../../extensions.md) | [Status](../../../../status.md) | [Identifiable](../../../../id.md) | [Custom Properties](../../../../extensions.md) | [Additional Properties](../../../../extensions.md) | Defined In |
|-------------------------------------|-----------------------------------------|---------------------------------|-----------------------------------|------------------------------------------------|----------------------------------------------------|------------|
| Can be instantiated | Yes | Experimental | No | Forbidden | Permitted | [mixins/experience-event/events/convert-lead.schema.json](mixins/experience-event/events/convert-lead.schema.json) |

## Convert Lead Example
```json
{}
```

# Convert Lead Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [xdm:leadOperation](#xdmleadoperation) | `object` | Optional | Convert Lead (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## xdm:leadOperation
### Lead Operation

`xdm:leadOperation`
* is optional
* type: `object`
* defined in this schema

### xdm:leadOperation Type


`object` with following properties:


| Property | Type | Required |
|----------|------|----------|
| `xdm:convertLead`| object | Optional |



#### xdm:convertLead
##### Convert Lead

undefined

`xdm:convertLead`
* is optional
* type: `object`

##### xdm:convertLead Type

Unknown type `object`.

```json
{
  "title": "Convert Lead",
  "type": "object",
  "properties": {
    "xdm:assignTo": {
      "title": "Assign To",
      "type": "string",
      "description": "."
    },
    "xdm:isSentNotificationEmail": {
      "title": "Is Sent Notification Email",
      "type": "boolean",
      "description": "Sent notification email."
    },
    "xdm:convertedStatus": {
      "title": "Converted Status",
      "type": "string",
      "description": "Converted status."
    }
  },
  "simpletype": "`object`"
}
```









