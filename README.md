# Construct-3-bugs

This is where we handle public bug report submissions for [Construct 3](https://www.construct.net/).

# Read these guidelines or your bug may be closed!

Many users file bugs which are useless because they don't contain enough information for us to do anything about them. We just close these bugs without investigating them. Please follow these guidelines to avoid having your bug closed and help make sure we can fix the bug you're reporting.

## Make sure it's really a bug

Many bug reports are actually just mistakes in events, or misunderstood features. Please double-check your events and the documentation.

## Use the bug report template

The bug submission page is pre-filled with a template. **We need all this information to help you.** Do not delete it. Please provide as much of the requested information as you can.

## A minimal project demonstrating the issue is required

Wherever possible, please include a **minimal project** demonstrating the issue. It is very common that the developers cannot reproduce a problem from the description alone. Including a minimal project makes it **much more likely the bug can be fixed**. You should **always** include a minimal project, even if the bug seems really simple, or you are an experienced user, because it **always helps**.

The project should be as minimal as possible, using the **fewest events and objects possible** to demonstrate the problem. Create a new empty project and try to reproduce the problem from scratch. Alternatively backup your project and delete as much as possible until the problem is isolated. Please continue as far as you can deleting any unrelated objects, event, layouts etc.

**Do not use third-party addons in your project.** Unfortunately we cannot provide support for third-party code. Bugs in third-party addons should be reported to their developers. We require that third-party addons are removed to prove that they are not causing the problem.

### How to include a project

Please save a single-file Construct 3 project. These have the file extension **.c3p**

You can save a project like this by choosing **Menu** -> **Project** -> **Save As** -> **Download a copy**.

The .c3p file can be shared publicly on free file hosting services like [Dropbox](https://www.dropbox.com), [https://onedrive.live.com](OneDrive) or [https://drive.google.com](Google Drive). Alternatively if you rename the .c3p ending to .zip, it can be attached to the GitHub issue. (GitHub will not accept a file ending in .c3p)

If you choose a different file host and it spams us with ads or asks us to sign up or enter information, we will not investigate the bug. We recommend the three services mentioned previously since they work well.

## Please only test the latest version of Construct 3

To avoid reporting bugs we've already fixed, please only test the latest version of Construct 3, including the latest beta release.

# Bug report FAQ

Here are answers to common questions or concerns during the bug report process. These really are asked frequently, so it's worth a look.

## Why did you close my bug report?

You need to follow all the guidelines in this post for the developers to actually have a reasonable chance of being able to diagnose and fix the problem you are trying to report. We get literally thousands of bug reports and dealing with them can be very time consuming. In order to save the developer's time so they can spend more time writing new and exciting features, and to save your time so you don't write useless reports which aren't useful to the developers, these guidelines are mandatory and reports not following them will be closed without investigation.

## You closed my report without investigating it. I'm offended!

Please do not be offended; we deal with large numbers of bug reports and our aim is to deal with them as efficiently as possible. We want to make sure you get in to the habit of filing useful, detailed, actionable bug reports which we can diagnose and fix quickly. This benefits you as well, since you are more likely to get your bug fixed, and sooner. So it is in everyone's interest that you learn to follow the guidelines to the fullest extent possible for every bug report. We may unceremoniously say that it is closed without investigation, but that is probably one out of 10 or 20 that day, and we want to highlight how you need to help us help you.

## My report was closed for not following the guidelines. What should I do next?

Please do not reply to closed bug reports. Instead, please file a new report, and make sure you follow all the guidelines and provide any missing information.

## Do I need to share my entire project? I have copyright concerns.

No, we don't want your entire project. Sending us your entire project is usually not actually helpful. The guidelines require a minimal project with the fewest events and objects possible. Preferably you will be able to demonstrate the problem by creating a new empty project, and adding the minimal events and objects to show what is happening. This is the only practical way for the developers to diagnose the problem. Projects with hundreds or even thousands of events or objects are a nightmare to test because there is so much going on in the engine and it is almost impossible to isolate which part is potentially going wrong. Further, a very significant proportion of bug reports are simply mistakes in events, and not actually bugs. Spending hours or even days debugging a huge project only to find it was a mistake in the events is simply too costly to our developer time, especially as we are a small team. Everyone wants the developers to get back to writing new and exciting features instead! Generally if you cannot reproduce the problem in a new empty project, that is a strong sign it is really just a mistake in your events, so this is a good way of filtering out mistakes from bug reports.

In your minimal project you can also easily use placeholder graphics instead of your actual artwork. This also removes any concern about copyright or having to sign NDAs. So it's better for both you and the developers.

## I can't reproduce the problem in a new project. What should I do?

This is a strong sign it is most likely a mistake in your own events. First of all, carefully review your events and make sure they are working correctly. Secondly, start isolating the problem. Back up your project and start deleting away chunks of it. At some point the problem may go away, which indicates the cause was in the last thing you deleted. In this case, go back and start removing smaller parts, and so on until you can identify exactly what is causing it. If it looks like a bug, use this as a starting point to demonstrate the bug in a new empty project. If the problem does not go away while you delete away content, you should be able to delete everything down all the way to a minimal project with no unnecessary events or objects. If you are sure the problem is a bug and not a mistake or misunderstanding of the events, then you can submit this project in a bug report.

## Why haven't you responded to my bug report yet?

We do look at every report, but developer and release schedules mean we may not get round to it immediately. Please allow a few weeks for it to be investigated. If you are waiting, you can improve the chance it is resolved when a developer does get round to it by carefully reviewing these guidelines and providing as much useful information about the problem as possible. If you are missing anything, you may end up waiting a few weeks for a reply simply asking for the missing information, and then you're back to waiting again.

## How do I report bugs in browsers?

Some bugs may conclude as really being bugs in the browser or platform, rather than being a problem with Construct. This includes any problem where the browser itself crashes or does a "sad tab" (where the tab replaces its content with a message saying it encountered a problem or crashed and you have to reload it) - Construct's code cannot normally cause this, only problems with the browser itself. You may be asked to report the problem directly to the browser maker instead. Here are the links to report problems in browsers:

Chromium (Google Chrome, NW.js, Cordova on Android): [crbug.com](https://crbug.com)

NW.js (issues that happen in NW.js only, and not the other Chromium-based platforms): [NW.js issues](https://github.com/nwjs/nw.js/issues)

Firefox: [Mozilla Bugzilla](https://bugzilla.mozilla.org/)

Edge / Windows Store apps: [EdgeHTML issue tracker](https://developer.microsoft.com/en-us/microsoft-edge/platform/issues/)

Safari (Mac, iOS, Cordova on iOS): [WebKit Bugzilla](https://bugs.webkit.org/)

# Get started

Thanks for reading our guidelines! You can get started by [visiting the Issues section](https://github.com/Scirra/Construct-3-bugs/issues).
