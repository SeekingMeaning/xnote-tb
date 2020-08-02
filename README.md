# XNote++

Persistent sticky notes for Thunderbird associated to mails.

This is a port to Thunderbird >= 3 based on XNote 2.1.0 (https://addons.mozilla.org/en-US/thunderbird/addon/3093) with bugfixes and additional features.

**XNote++ will not work with Thunderbird versions after 68 as [support for legacy extensions has been dropped](https://developer.thunderbird.net/add-ons/updating/tb78) and updating would require more effort than I can spend. Unless someone steps up and takes the effort to rewrite this add-on, please get prepared to save your notes and find an alternate solution.**

**After receiving some requests and searching for a way how to support the effort on finding someone who would like to pick up that task I've created an [issue on bountysource](https://www.bountysource.com/issues/92160540-add-support-for-thunderbird-78). Maybe that helps to motivate someone to do the porting. Of course, enough backers will be required as well ;-)**

XNote allows you to create a note for each mail. Thus, you can add for example the phone number of that contact or when you have to contact the sender back.

## Features

- Add notes to messages
- Custom column to mark messages with notes.
- Highlight messages with notes.
- Resizeable notes
- Translated into Dutch, English, French, Galician, German, Italian, Japanese, and Polish.

## Some notes on **usage**

- _XNote toolbar button:_ XNote comes with a button to add a note to a message. To enable this button, right click on the toolbar (the bar with the icons below the menu bar) and select "Customize...". Locate the "XNote" button and drag it onto your toolbar. Then select "Done" in the customization window.
- _XNote column:_ If you want to see the "Notes" column, you have to add it via a (left-)click on the rightmost icon in the column headers of the e-mail list (above the scrollbar).

See http://www.froihofer.net/xnote/ for version information, FAQs, and open issues - and please do not use the review functionality below (Mozilla add-ons page) for bug reports.

## Upgrade to Thunderbird 68

- The latest version is compatible with TB 68, but it seems that Thunderbird fails to automatically update the add-on in some cases. If this is the case, please update manually by downloading the latest compatible version from here.
- Some people have reported that the XNote toolbar button and/or the XNote column is missing after an upgrade to Thunderbird 68. It looks like there is already a Thunderbird bug for this (https://bugzilla.mozilla.org/show_bug.cgi?id=1584160) which should be fixed in TB 68.3 - PreRelease Build already available: http://ftp.mozilla.org/pub/thunderbird/candidates/68.3.0-candidates/build1/

Possible workaround: Use the context menu of the message list (right mouse click).

## Kown major issues

- Notes window disappears if moved too quickly. This was introduced by some Thunderbird version < 35 and I assume it to be a bug in Thunderbird's dialog movement handling. If this happens, the note's position can be reset to the default location using the context menu in the message list.
