# hubot-cfa-brigade-checkin

A hubot script that allows CfA brigade checkins from Slack.

See [`src/cfa-brigade-checkin.coffee`](src/cfa-brigade-checkin.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-cfa-brigade-checkin --save`

Then add **hubot-cfa-brigade-checkin** to your `external-scripts.json`:

```json
["hubot-cfa-brigade-checkin"]
```

## Sample Interaction

```
user1>> hubot checkin
hubot>> Successfully checked user1 into 'Civic Hack Night'!
user2>> hubot checkin @alice @bob Some Other Event
hubot>> Successfully checked alice into 'Some Other Event'!
hubot>> Successfully checked bob into 'Some Other Event'!
```
