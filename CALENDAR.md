# Pixels Camp Calendar

This page explains how you can add the Pixels Camp schedule to your favorite desktop or mobile calendar app and make sure it's always up to date.

You can always find and use the web version (mobile responsive) at this address: https://pixels.camp/schedule/

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



### iPhone iOS: Calendar

## Improve this

If you want to improve this page with more devices then go ahead and make a pull request. Make it clear and pretty.
