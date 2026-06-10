# ToTheFront

ToTheFront is a lightweight macOS menu bar utility that fixes an annoying windowing behavior: when you click a background window from another app, macOS may only bring that one window forward. ToTheFront brings the whole app forward together, so related windows stay grouped the way you expect.

It stays out of the way, lives in the menu bar, launches fast, and focuses on one job: making multi-window apps feel more consistent.

## Why It Exists

If you work with Finder, Xcode, CotEditor, BBEdit, Terminal, browsers, or any app that commonly has several windows open at once, you have probably seen this:

- You click a background window.
- macOS activates the app.
- But sibling windows can remain buried behind other apps.

ToTheFront fixes that moment. Click one background window, and the app comes forward as a group.

## What It Does

- Detects clicks on background app windows
- Activates the clicked app and brings its windows forward together
- Runs as a native AppKit menu bar utility
- Lets you enable or disable behavior instantly
- Supports optional app filtering so you can exclude apps or include only selected apps
- Offers modifier-key behavior so activation can be always on, shift-to-activate, or shift-to-bypass
- Can show in the menu bar, Dock, or both depending on your preference

## Built for macOS

ToTheFront is a native macOS app written in Swift with AppKit. It is not an Electron app, not a browser wrapper, and not a background script bundle pretending to be an app.

The app is designed to feel at home on macOS:

- Menu bar utility design
- Native settings window
- Native app list and file picker
- Minimal idle CPU usage
- Direct-download friendly packaging

## Who It Is For

ToTheFront is especially useful if you:

- Work with multiple Finder windows across projects
- Keep several editor or terminal windows open at once
- Use more than one display
- Prefer click-to-focus behavior that feels more predictable
- Want a small utility instead of a large window manager

## Key Features

### Bring the whole app forward

Clicking a background window should not leave the rest of that app scattered behind other apps. ToTheFront promotes the app as a unit, which makes multi-window workflows feel cleaner and faster.

### App filtering

You can decide how broadly the behavior applies:

- Exclude these apps
- Include only these apps

This makes it easy to keep the behavior system-wide while carving out exceptions, or to limit it to only a few apps where it is most useful.

### Modifier-key control

You can choose how the Shift key affects activation:

- Do Nothing
- Activate System
- Deactivate System

That gives you a quick way to make the behavior conditional without opening settings.

### Simple, visible controls

From the menu bar you can:

- Open Settings
- Enable or disable the app
- Quickly add or remove the current app from your list
- Quit the utility

## Why Not a Full Window Manager?

Because sometimes you do not want one.

ToTheFront does not try to tile windows, replace Mission Control, script the desktop, or impose a new workspace model. It solves one specific frustration with as little friction as possible.

## Installation

Download the latest DMG, open it, drag **ToTheFront** into **Applications**, and launch it.

On first run, macOS may ask you to confirm background or login-item related behavior depending on your configuration and OS version.

## Privacy

ToTheFront is a local desktop utility. It does not need an account, and it does not depend on a remote service to do its job.

## Summary

ToTheFront makes macOS feel more coherent for multi-window work. If you have ever clicked a background window and wondered why the rest of that app stayed behind, this utility is for you.
