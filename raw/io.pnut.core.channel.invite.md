<!-- give your raw a title -->
# Channel Invite

<!-- specify the "type" for your raw -->
> ### io.pnut.core.channel.invite

<!-- provide a description of what your raw represents -->
The channel invite raw can be used to indicate that a post or message is an invitation to join in a conversation taking place in a channel. 

<!-- provide at least one example of what your raw might look like in the wild -->
## Example

~~~ js
{
    "type": "io.pnut.core.channel.invite",
    "value": {
        "channel_id": "18"
    }
}
~~~

<!-- provide a complete description of the fields in the "value" object for your raw -->
## Fields

| Field        | Required? | Type   | Description                                                        |
| -----        | --------- | ----   | -----------                                                        |
| `channel_id` | Required  | string | A valid channel id. |

<!-- provide a way to contact you -->
## Maintainers
* @33MHz

<!-- provide references to compatible apps / service -->
## Used by
* [Patter](https://patter.chat)