# Changelog

## 2.1.3

- Remote access from the local screen is more reliable: cancelling while the browser is approving no longer leaves a half-finished link, and approving with a different Grablo account is refused instead of connecting the device to the wrong account.
- A pending connection request is withdrawn once the device is linked, so the code cannot be used again.

Full release notes: https://grablo.co/news

## 2.1.2

- Remote access can now be turned on from the local screen: connect a Grablo account to view cameras from anywhere at spot.grablo.co and get phone alerts, with no port forwarding.
- A device registered to another account is not connected; you are asked to remove it from that account first.

Full release notes: https://grablo.co/news

## 2.1.1

- Fixed a crash when the cloud connection reconnects while messages are being sent.
- Messages, the local screen and setup are now available in 17 languages; the language follows your choice, or your system language.

Full release notes: https://grablo.co/news

## 2.1.0

- Sound detection: alerts can now trigger on sounds a camera hears (for example glass breaking, a dog barking or a siren).
- Live camera sound in the viewer.
- Media play comes with 14 built-in sounds (sirens, alarms, doorbell, chimes), with the burglar alarm siren picked by default.
- Home Assistant sensors now carry what was detected (type, name, license plate, camera, zone and confidence) as attributes.
- The limit of 63 alert rules is gone.
- Fixed gaps in recording around stop and start, deleting recorded segments, and slow stops when saving settings on slow disks.

Full release notes: https://grablo.co/news

## 2.0.1

- Language selection on the local screen sign-in and account creation screens.
- Fixed an unreachable camera interrupting other camera streams about every 90 seconds.
- Storage folders that contain other files or do not exist are now blocked before saving.
- Fixed linking a device set up on the local screen to a Grablo account creating a separate empty place.
- The local screen shows the PC name as the device name.

Full release notes: https://grablo.co/news

## 2.0.0

- First Grablo Spot add-on. Spot now has its own add-on and version line, separate from Grablo IoT Core.

Full release notes: https://grablo.co/news
