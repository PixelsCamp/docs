# Pixels Camp Calendar

This page explains how you can add the Pixels Camp schedule to your favorite desktop or mobile calendar app and make sure it's always up to date.

You can always find and use the web version, which is mobile responsive and has a pretty printable version, at this address: https://pixels.camp/schedule/

## Technical details

We provide two endpoints for the calendar:

 * JSON version: https://api.pixels.camp/cal/json
 * ICS version: https://api.pixels.camp/calendar/cal.ics

**Be aware** that you should always request the latest feed when presenting calendar information in any context. The calendar is constantly changing until the event starts (sometimes it changes during the event), so it's unwise to assume it's a static file.

The **DESCRIPTION** field has been extended to support a few extra attributes we need using a readable simple syntax. Here's how:

```
This is the talk long description text.
Awesome talk about security, progressive web apps, conversational bots,
productivity tools and whatnot, all in one, presented by two speakers.

[speaker: John Doe, https://pixels.camp/doe]
[speaker: Mad Max, https://pixels.camp/madmax]
[language: English]
```

## Subscribe the calendar in your device

### Mac OSX: Calendar

Open your default Calendar.app

Go to Menu > File > New Calendar Subscription

![Screenshot](https://github.com/PixelsCamp/docs/blob/master/img/osx_start.png?raw=true)

Enter the .ics endpoint https://api.pixels.camp/calendar/cal.ics

In the Location you can either choose "On My Mac" or iCloud (and then you'll have it in your iOS devices too)

Make sure it Auth-refreshes every hour

![Screenshot](https://github.com/PixelsCamp/docs/blob/master/img/osx_settings.png?raw=true)

And you're done

![Screenshot](https://github.com/PixelsCamp/docs/blob/master/img/osx_subscribed.png?raw=true)

### iPhone iOS: Calendar

Subscribing calendars directly on the iPhone/iPad is surprisingly hard and very well hidden. But there's a way.

Launch the **Settings app** and tap on **Mail, Contacts, Calendars**.

Tap on **Add Account**, under the Mail section.

Tap on **Other**.

Tap on **Add Subscribed Calendar** under the Other section.

Enter the .ics endpoint https://api.pixels.camp/calendar/cal.ics

Tap Next and you're done.

You can't specify the auto-refresh time like on OSX, but we guess it's frequent.

![Screenshot](https://github.com/PixelsCamp/docs/blob/master/img/ios_calendar.png?raw=true)

### Android/Google Calendar

You can't subscribe calendars directly using the Google Calendar app on Android. Instead, go to http://calendar.google.com and follow these steps:

On the left side, find "Other calendars" and click the down arrow.

Select Add by URL.

Enter the calendar's address https://api.pixels.camp/calendar/cal.ics in the field provided.

Click Add calendar. The calendar will appear on the left side under "Other calendars" and also on your Android device.


## Improve this

If you want to improve this page with more devices then go ahead and make a pull request. Make it clear and pretty.
