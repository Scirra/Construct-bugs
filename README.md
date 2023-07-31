# Construct bug reports

This is where we handle public bug report submissions for [Construct 3 and Construct Animate](https://www.construct.net/).

# Read these guidelines or your bug may be closed!

Unfortunately, many users file bugs which are useless because they don't contain enough information for us to do anything about them. Our policy is to close these bugs without investigating them. Please follow these guidelines to avoid having your bug closed and help make sure we can fix the bug you're reporting.

## Always follow the guidelines, every time

Most bugs are not actually obvious, even if they look obvious to you. Often issues actually only happen in a very specific set of circumstances, which you happen to have. These guidelines are designed to make sure we can figure out what's going on. So please never skip any part of the guidelines, no matter how obvious you think the problem is, or how many issues you've filed before - we really need all this information every time, and skipping any details will likely make it much more difficult for us to help you.

## Make sure it's really a bug

Many bug reports are actually just mistakes in events, or misunderstood features. Please double-check your events and the documentation.

## Please check the latest version of Construct

To avoid reporting bugs we've already fixed, please verify the issue happens in the latest version of Construct, including the latest beta release.

- Construct 3: [open the latest beta release here](https://editor.construct.net/beta) or [view all Construct releases here](https://www.construct.net/en/make-games/releases).
- Construct Animate: [open the latest beta release here](https://animate.construct.net/beta) or [view all Construct releases here](https://www.construct.net/en/animation-software/releases).

If something used to work but was accidentally broken by an update, it is very useful to tell us **which release it broke in.** This is what the *First affected release* field of the bug report template is for. For example if something worked in all releases up to r300, and was then broken in all releases from r301 onwards, then please enter r301 as the first affected release. (Please don't just enter whichever version you happened to test, as this is misleading and could make it take longer to deal with the issue.)

## Use the bug report template

The bug submission page is pre-filled with a template. Do not delete it - **we need all this information to be able to help you.** Please provide as much of the requested information as you can, including the system details or crash report information with every report. Provide this information in full every time - don't refer to other issues, forum posts elsewhere, etc. so the report includes all the necessary information by itself.

## Only mention one problem per issue

Please only describe one problem in each issue you create. It's very confusing to have two separate descriptions at once and usually means you skipped some important information for one of them. Additionally we have useful tools to assign and track issues, but these are only effective if an issue refers to a single problem.

## A minimal project demonstrating the issue is required

Wherever possible, please include a **minimal project** demonstrating the issue. If you do not include a project, your report will most likely be closed without investigation, even if you provided a written description or think the problem is obvious. This is because without a project file, we almost always find everything working fine. Usually there is something specific to your project that actually causes the problem, and it's impossible to help without it. Therefore attaching a project is required.

The project should be as minimal as possible, using the **fewest events and objects possible** to demonstrate the problem. Create a new empty project and try to reproduce the problem from scratch. Alternatively backup your project and delete as much as possible until the problem is isolated. Please continue as far as you can deleting any unrelated objects, event, layouts etc.

**Do not use third-party addons in your project.** Unfortunately we cannot provide support for third-party code. Bugs in third-party addons should be reported to their developers. We require that third-party addons are removed to prove that they are not causing the problem.

### How to include a project

Please save a single-file project. These have the file extension **.c3p**

You can save a project like this by choosing **Menu** -> **Project** -> **Save As** -> **Download a copy**.

The .c3p file can be shared publicly on free file hosting services like [Dropbox](https://www.dropbox.com), [OneDrive](https://onedrive.live.com) or [Google Drive](https://drive.google.com). Alternatively if you add the file to a zip, or rename the .c3p extension to .zip, it can be attached to the GitHub issue. (GitHub will not accept a file ending in .c3p. Also, Construct can still directly open projects from a zip if it is actually a .c3p file.)

If you choose a different file host and it spams us with ads, asks us to sign up or enter information, or expires by the time we look at it, we will not investigate the bug. We recommend the three services mentioned previously since they work well.

### The ideal project attachment

We deal with thousands of reports, and many are difficult problems. To help us quickly and effectively deal with your issue, it is ideal to provide a project demonstrating the issue which:

- has the fewest events and objects possible
- is automatic (not requiring any user input, since it varies a lot between people and simplifies the steps to reproduce)
- reproduces the problem as quickly as possible (within a couple of seconds or with the fewest necessary steps to follow after opening the project)

## A project is more useful than a video

Often users attach videos with bug reports. This is not always as useful as you might think: we cannot debug videos to figure out what is going on. Attaching a project is far more useful. Additionally reports with short and well-written steps to reproduce are usually quicker to deal with, which is important given that we deal with thousands of reports.

In general you can probably skip attaching a video unless we ask for one. They can be helpful if we are having trouble reproducing the problem from the written steps to reproduce, since we can watch exactly what you are doing. If you don't mind sparing the time, you could attach a video alongside written steps to reproduce just in case we need it.

## Issues must have real-world relevance

With a complex piece of software like Construct, it can be possible to create deliberately obscure projects, or intentionally obscure sequences of steps, that can produce unexpected results or even crashes. However if nobody using Construct in a normal fashion ever encounters such problems, then they have no relevance to the real-world usage of Construct. We are committed to developing robust, quality software that customers can depend on. However we have found that fixing such issues is basically a waste of time, and can in fact degrade the quality of Construct, as every change carries a risk of causing other problems. So while in theory it is useful to report such issues "just in case" someone runs in to it, in practice it is not. We are a small team with limited resources, and we want to focus our limited time on supporting people using Construct for real-world purposes, rather than dealing with difficult and time-consuming problems that are irrelevant to customers. So we may sometimes close issues without fixing them if we feel the report involved deliberately hunting for problems, or otherwise does not represent realistic use of Construct.

## Community guidelines
Our staff are here to help you. We have experienced engineers who have dealt with thousands of bug reports. The vast majority of reporters are helpful and are happy to work with us. However if you don't co-operate or are unnecessarily combative in dealing with staff, we will close your report and stop investigating it. We will resume investigation on the report if someone files it complying with the guidelines. For more details please refer to the [Forum & Community guidelines](https://www.construct.net/en/forum/general/open-topic-33/forum-community-guidelines-141035) which also apply to bug reports.

# Bug report FAQ

Here are answers to common questions or concerns during the bug report process. These really are asked frequently, so it's worth a look.

## Why did you close my bug report?

You need to follow all the guidelines in this post for the developers to actually have a reasonable chance of being able to diagnose and fix the problem you are trying to report. We get literally thousands of bug reports and dealing with them can be very time consuming. In order to save the developer's time so they can spend more time writing new and exciting features, and to save your time so you don't write useless reports which aren't useful to the developers, these guidelines are mandatory and reports not following them will be closed without investigation.

## You closed my report without investigating it. I'm offended!

Please do not be offended; we deal with large numbers of bug reports and our aim is to deal with them as efficiently as possible. We want to make sure you get in to the habit of filing useful, detailed, actionable bug reports which we can diagnose and fix quickly. This benefits you as well, since you are more likely to get your bug fixed, and sooner. So it is in everyone's interest that you learn to follow the guidelines to the fullest extent possible for every bug report. We may unceremoniously say that it is closed without investigation, but that is probably one out of several that day, and we want to highlight how you need to help us help you.

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

Chromium (Google Chrome, Microsoft Edge, NW.js, Cordova on Android): [crbug.com](https://crbug.com)

Safari (Mac, iOS, Cordova on iOS): [WebKit Bugzilla](https://bugs.webkit.org/)

Firefox: [Mozilla Bugzilla](https://bugzilla.mozilla.org/)

NW.js (issues that happen in NW.js only, and not the other Chromium-based platforms): [NW.js issues](https://github.com/nwjs/nw.js/issues)

# Get started

Thanks for reading our guidelines! You can get started by [visiting the Issues section](https://github.com/Scirra/Construct-3-bugs/issues).
