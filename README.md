# Construct 3 bug reports

This is where we handle public bug report submissions for [Construct 3](https://www.construct.net/).

# Read these guidelines or your bug may be closed!

Many users file bugs which are useless because they don't contain enough information for us to do anything about them. We just close these bugs without investigating them. Please follow these guidelines to avoid having your bug closed and help make sure we can fix the bug you're reporting.

## Make sure it's really a bug

Many bug reports are actually just mistakes in events, or misunderstood features. Please double-check your events and the documentation.

## Use the bug report template

The bug submission page is pre-filled with a template. **We need all this information to help you.** Do not delete it. Please provide as much of the requested information as you can, including the system details or crash report information with every report.

## A minimal project demonstrating the issue is required

Wherever possible, please include a **minimal project** demonstrating the issue. It is very common that the developers cannot reproduce a problem from the description alone. Including a minimal project makes it **much more likely the bug can be fixed**. You should **always** include a minimal project, even if the bug seems really simple, or you are an experienced user, because it **always helps**.

The project should be as minimal as possible, using the **fewest events and objects possible** to demonstrate the problem. Create a new empty project and try to reproduce the problem from scratch. Alternatively backup your project and delete as much as possible until the problem is isolated. Please continue as far as you can deleting any unrelated objects, event, layouts etc.

**Do not use third-party addons in your project.** Unfortunately we cannot provide support for third-party code. Bugs in third-party addons should be reported to their developers. We require that third-party addons are removed to prove that they are not causing the problem.

### How to include a project

Please save a single-file Construct 3 project. These have the file extension **.c3p**

You can save a project like this by choosing **Menu** -> **Project** -> **Save As** -> **Download a copy**.

The .c3p file can be shared publicly on free file hosting services like [Dropbox](https://www.dropbox.com), [OneDrive](https://onedrive.live.com) or [Google Drive](https://drive.google.com). Alternatively if you add the file to a zip, it can be attached to the GitHub issue. (GitHub will not accept a file ending in .c3p. Also, Construct 3 can still directly open projects from a zip if it contains a single .c3p file.)

If you choose a different file host and it spams us with ads or asks us to sign up or enter information, we will not investigate the bug. We recommend the three services mentioned previously since they work well.

### The ideal project attachment

We deal with thousands of reports, and many are difficult problems. To help us quickly and effectively deal with your issue, it is ideal to provide a project demonstrating the issue which:

- has the fewest events and objects possible
- is automatic (not requiring any user input, since it varies a lot between people and simplifies the steps to reproduce)
- reproduces the problem as quickly as possible (within a couple of seconds)

## A project is more useful than a video

Often users attach videos with bug reports. This is not always as useful as you might think: we cannot debug videos to figure out what is going on. Attaching a project is far more useful. Additionally reports with well-written steps to reproduce are usually quicker to deal with, which is important given that we deal with thousands of reports.

In general you can probably skip attaching a video unless we ask for one. They can be helpful if we are having trouble reproducing the problem from the written steps to reproduce, since we can watch exactly what you are doing. If you don't mind sparing the time, you could attach a video alongside written steps to reproduce just in case we need it.

## Please only test the latest version of Construct 3

To avoid reporting bugs we've already fixed, please only test the latest version of Construct 3, including the latest beta release.

## Voting on bugs
You can add a "+1" reaction to a bug report to indicate you are also interested in that bug. When viewing an issue, there is an "Add your reaction" button in the top-right corner. Click on that and select the "thumbs up" (+1) reaction.

This provides a basic voting system, so we can better prioritise issues that many people have voted for.

You can also subscribe to issues using the button to the right of the issue. This will create a notification on GitHub whenever the issue is updated.

## Don't troll the developers
Our staff are here to help you. We have experienced engineers who have dealt with thousands of bug reports. The vast majority of reporters are helpful and are happy to work with us. However if you don't co-operate or are unnecessarily combative in dealing with staff, we will close your report and stop investigating it. We will resume investigation on the report if someone files it complying with the guidelines.

The following list are behaviors we will see as trolling. If too many of these behaviors occur in one report it is liable to be closed.

- Insisting developers investigate the issue over holidays or weekends. Please be patient.
- Repeatedly nagging developers to investigate an issue ahead of schedule, or repeatedly bumping the thread.
- Exaggerating the impact of an issue, or otherwise acting as if your issue is so serious, it is the end of the world. This is rarely the case, especially if the issue is not new. Diverting attention can also end up postponing work on other genuinely more serious issues, harming other users. It is also unnecessarily aggravating.
- Constantly treating the developers with scepticism or distrust. We are not perfect, but we are experienced engineers. Please have a little faith. Sometimes we discuss the issue and make educated guesses. However there is no need to try to argue us down every time we say something; it is simply a waste of everyone's time.
- Throwing in unrelated bugs or gripes. Please don't muddy the waters by talking about unrelated issues, complaining about why your favourite feature is not implemented yet, etc. Fixing a bug is difficult enough as it is, and having a concise, focused approach gives us the best chance of fixing it.
- Blaming us before the issue has been fully identified. All software depends on a wide range of third parties, such as OS developers, compiler and library authors, driver developers, browser makers, and so on. We do routinely fix or work around issues which are not directly our fault, in order to try to make sure Construct works as well as possible. If we point to a third-party cause, it does not necessarily mean we are trying to avoid fixing it, although it may make it significantly more difficult. Our normal routine investigation simply involves identifying the root cause before we proceed to mitigating it. There is no reason to launch in to a rant about how it's all our fault. Often this is simply incorrect and may also cause embarrassment.
- Demanding a resolution when none is practical. Some issues will have no good resolution, such as an issue caused by a specific graphics driver version on a particular OS and hardware combination. It is not feasible to investigate such issues, particularly if the evidence suggests the problem is not in our code. It is also unreasonable to demand an explanation of the inner workings of these other pieces of software we've had no part in developing.
- Accusing us of not responding or not caring about the issue, particularly after we have already put effort in to responding or investigating it
- Arguing about whether or not what you did qualifies as trolling or not ("meta-trolling"). It is up to the judgement of our staff.

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
