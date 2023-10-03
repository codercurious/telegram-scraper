# Telegram scraper and adder

Scrape any telegram group members and add them to your group

Scrape and export telegram channel messages

https://youtu.be/j_vSazbotQ8

✳️ **You might be interested in:** [Whatsapp scraper](https://apify.com/curious_coder/whatsapp-scraper) | [Discord scraper](https://apify.com/curious_coder/discord-data-scraper) | [Facebook group members scraper](https://apify.com/curious_coder/facebook-scraper) | [Other useful scrapers](https://apify.com/curious_coder)

Here is the sample output of this actor:

## Group members output

```json
{
	"flags": 33554543,
	"self": false,
	"contact": false,
	"mutualContact": false,
	"deleted": false,
	"bot": false,
	"botChatHistory": false,
	"botNochats": false,
	"verified": false,
	"restricted": false,
	"min": false,
	"botInlineGeo": false,
	"support": false,
	"scam": false,
	"applyMinPhoto": true,
	"fake": false,
	"botAttachMenu": false,
	"premium": false,
	"attachMenuEnabled": false,
	"flags2": 0,
	"botCanEdit": false,
	"id": "202577853",
	"accessHash": "-2127225199806290195",
	"firstName": "Pavel",
	"lastName": "Tsyganov",
	"username": "Tsyganov_pro",
	"phone": null,
	"photo": {
		"flags": 2,
		"hasVideo": false,
		"personal": false,
		"photoId": "870065253985134518",
		"strippedThumb": {
			"type": "Buffer",
			"data": [
				"<... buffer data ...>"
			]
		},
		"dcId": 2,
		"className": "UserProfilePhoto"
	},
	"status": {
		"className": "UserStatusRecently"
	},
	"botInfoVersion": null,
	"restrictionReason": null,
	"botInlinePlaceholder": null,
	"langCode": null,
	"emojiStatus": null,
	"usernames": null,
	"className": "User"
}
```

## Group messages output 

```json
{
	"flags": 11567744,
	"out": false,
	"mentioned": false,
	"mediaUnread": false,
	"silent": false,
	"post": false,
	"fromScheduled": false,
	"legacy": false,
	"editHide": true,
	"pinned": false,
	"noforwards": false,
	"id": 1677520,
	"fromId": null,
	"peerId": {
		"channelId": "1159345367",
		"className": "PeerChannel"
	},
	"fwdFrom": null,
	"viaBotId": null,
	"replyTo": null,
	"date": 1689899815,
	"message": "Sign up using code BITBOY and receive a 200% bonus on your first deposit up to $1,000💰 \n\nstake.com/?c=BitBoy",
	"media": {
		"flags": 1,
		"spoiler": false,
		"photo": {
			"flags": 0,
			"hasStickers": false,
			"id": "5030599717138049863",
			"accessHash": "-9016904732152496874",
			"fileReference": {
				"type": "Buffer",
				"data": [
					"<... buffer data ...>"
				]
			},
			"date": 1689899815,
			"sizes": [
				{
					"type": "i",
					"bytes": {
						"type": "Buffer",
						"data": [
							"<... buffer data ...>"
						]
					},
					"className": "PhotoStrippedSize"
				},
				{
					"type": "m",
					"w": 240,
					"h": 320,
					"size": 17007,
					"className": "PhotoSize"
				},
				{
					"type": "x",
					"w": 599,
					"h": 800,
					"size": 65548,
					"className": "PhotoSize"
				},
				{
					"type": "y",
					"w": 958,
					"h": 1280,
					"sizes": [
						8335,
						20682,
						35329,
						50297,
						82454
					],
					"className": "PhotoSizeProgressive"
				}
			],
			"videoSizes": null,
			"dcId": 1,
			"className": "Photo"
		},
		"ttlSeconds": null,
		"className": "MessageMediaPhoto"
	},
	"replyMarkup": null,
	"entities": [
		{
			"offset": 90,
			"length": 19,
			"className": "MessageEntityUrl"
		}
	],
	"views": null,
	"forwards": null,
	"replies": {
		"flags": 0,
		"comments": false,
		"replies": 0,
		"repliesPts": 2660889,
		"recentRepliers": null,
		"channelId": null,
		"maxId": null,
		"readMaxId": null,
		"className": "MessageReplies"
	},
	"editDate": 1689923336,
	"postAuthor": null,
	"groupedId": null,
	"reactions": {
		"flags": 6,
		"min": false,
		"canSeeList": true,
		"results": [
			{
				"flags": 0,
				"chosenOrder": null,
				"reaction": {
					"emoticon": "👍",
					"className": "ReactionEmoji"
				},
				"count": 1,
				"className": "ReactionCount"
			}
		],
		"recentReactions": [
			{
				"flags": 0,
				"big": false,
				"unread": false,
				"peerId": {
					"userId": "6199150375",
					"className": "PeerUser"
				},
				"date": 1689923336,
				"reaction": {
					"emoticon": "👍",
					"className": "ReactionEmoji"
				},
				"className": "MessagePeerReaction"
			}
		],
		"className": "MessageReactions"
	},
	"restrictionReason": null,
	"ttlPeriod": null,
	"className": "Message"
}
```

## Auto adder
Once you run the telegram auto adder feature, you will start seeing members getting added to your group as shown in the screenshot

![Telegram auto adder result](https://awesomescreenshot.s3.amazonaws.com/image/1021927/43174900-371db09a52a8d6385d1b752c9b372003.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJSCJQ2NM3XLFPVKA%2F20230926%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230926T132117Z&X-Amz-Expires=28800&X-Amz-SignedHeaders=host&X-Amz-Signature=236e1b29ac6568d03b5be8b1fb57b4e3afc0b163d9f6913738658bff2b1e486a)
