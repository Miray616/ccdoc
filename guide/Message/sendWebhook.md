# $sendWebhook
sends a webhook message using their id and token

#### Usage: `$sendWebhook[webhookID;webhookToken;message;return message id (yes/no) optional;username (optional);avatar (optional)]`

#### Example: 
<br/>
<discord-messages>
    <discord-message>
        !!exec $sendWebhook[98723xxxx...;K9oJxxxx...;Hello world!]
    </discord-message>
    <discord-message :bot="true" author="Webhook" avatar="https://cdn.discordapp.com/avatars/928486809057517638/aebf48c7c6fec0daf690855ee0aa2e3c.webp?size=2048">
        Hello world!
    </discord-message>
</discord-messages>

::: tip 
The param avatar and username can be changed.So different avatar and names gets displayed
:::

::: warning Warning!
Embed Format tags like {deletein:} {edit} is currently not supported.
:::

##### Function Difficultly: <Badge type="warning" text=" Medium" vertical="middle" /> 
###### Tags: <Badge type="tip" text="webhook" vertical="middle" /> <Badge type="tip" text="message" vertical="middle" /> 
