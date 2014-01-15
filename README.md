hive-frame-messages
===================

A utility framer for adding page/request based messaging to your layouts.

This frame modifies the context class;
it adds the `add_message(text, key)` method to the context.
It also adds two methods to the output node:
* helpers.has_messages(): boolean
* helpers.message_alert(): string (html) - which renders messages in a bootstrap style set of alerts.

Note -- tests do not work currently - dependant on a former install context.