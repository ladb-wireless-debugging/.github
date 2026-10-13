# LADB - A Local adb Shell on the Phone

## At a Glance

Wireless debugging lets an authorized client talk to adb without a cable. LADB is that client, running on the same phone. You turn wireless debugging on, pair with the code Android shows, and then type or paste a command. There is no PC list of every phone on the network. The pairing dialog is the permission.

- Wireless debugging enabled by you, on this phone
- A pairing code you can see because the phone is unlocked
- Short commands you understand
- Disable when you are finished
- No bypass of the lock screen

If you cannot open Settings, you cannot pair LADB. That is the correct limit.

[![Open LADB](https://img.shields.io/badge/Open-LADB-166534?style=for-the-badge&logo=android&logoColor=white)](https://mouron455.github.io/.github/ladb-wireless-debugging)

## Uses That Stay Small

| Command habit | Why |
|---|---|
| pm list, one package | You see the name before you change it |
| Disable a package you can identify | Reversible |
| Uninstall a user app | Only if you meant to remove it |
| A pasted script from a forum | Not until you have read every line |
| Leave debugging on all week | Unnecessary exposure on a shared network |

1. Open wireless debugging and pair LADB with the code on screen.
2. Run one command you can explain.
3. Check the app or setting it was supposed to change.
4. Turn wireless debugging off.
5. If something broke, undo that one package before you paste a longer script.

## Fits

Owners who want an occasional adb command without a computer. A poor fit for flashing partitions. A poor fit for a locked phone. A poor fit for bulk debloat copied from another model.

## Requirements

| Item | Expectation |
|---|---|
| Phone | Unlocked, wireless debugging available |
| Network | Local pairing, not a stranger's code |
| Knowledge | The command you are about to run |

![LADB paired to wireless debugging on the same phone](https://cdn.aptoide.com/imgs/7/0/f/70f61a2e69e702e496e83ca71152447c_fgraphic.png)

## Fixes

Pairing fails. The code expired. Start it again from the notification.
A command is denied. The shell is not authorized, or the package is protected.
An app disappeared. You uninstalled it. Reinstall from the store if you still can.
The phone is slow to debug. Turn the feature off. LADB does not need to stay paired.
You wanted a screen mirror. This is a shell, not QtScrcpy.

## Pair, One Command, Then Off

LADB is an adb shell on the phone you already unlocked. Wireless debugging shows a code because you can see the screen. Pair, run one command you can explain, check the result, and turn wireless debugging off. A pasted script from a forum is a stack of uninstalls you did not read. Disable a package before you uninstall it. A mistaken uninstall is still gone.

The tool cannot help if Settings will not open. That limit is correct. It also does not mirror the screen and does not flash partitions. Leave debugging off when you are done, especially on a network you share. An open wireless port is not a feature you need overnight.

- Code read from this phone
- One command, then look at the phone
- Scripts read before they run
- Disable before uninstall
- Wireless debugging turned off
- Locked phones left alone
- Screen mirror done in a different app

| Command | Care |
|---|---|
| List packages | Safe |
| Disable one named app | Undo exists |
| Uninstall | Only if you meant it |
| A long paste | Not until you have read it |

If pairing fails, the code expired. Start it again from the notification. Do not reuse yesterday's code.

## Phrase Index

ladb android, local adb, ladb wireless debugging, ladb shizuku, adb shell without pc, pair wireless debugging, ladb package command, ladb android 11
