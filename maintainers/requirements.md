## Required skills ##

- The maintainer must have an account on Github, Gerrit and JIRA.

- The maintainer must know how to use Gerrit correctly. This includes but is not limited to pushing commits, rebasing commits, reviewing commits, pushing commits in draft, assigning proper groups for further testing and organizing large number of commits in topics.

- The maintainer must know how to use Git correctly. This includes but is not limited to amending commits, rebasing commits, cloning repos, pushing commits/repos, merging and pulling commits accordingly. 

- The maintainer must know how to use JIRA correctly. This includes but is not limited to reviewing reports and replying accordingly to users. The maintainer will also be required to handle any device specific issues on their own. If the maintainer needs assistance then assistance will be provided.

- The maintainer must display proper authorship and commit history in all non-original commits that are pulled from other sources. This is not limited to just past commits but future commits as well that are pushed to both github and gerrit. Authorship is important.



## Device requirements ##

- The device must be buildable.

- The device must not have any outside dependencies. All dependencies must be open sourced and ready to be forked with proper authorship/commit history.

- The device must enforce SELinux.

- The device's kernel must be upstreamed with the latest patches from kernel.org.

- The device must have working audio. This includes but is not limited to in-call audio, speaker phone, headphone jack and bluetooth audio.

- The device must have working phone calls and data. This includes but not limited to being able to receive and make phone calls, download files from the internet, stream video calls and use different sim slots if applicable.

- The device must have a working hotspot if applicable. This includes but not limited to WiFi and USB tethering.

- The device must have a working camera. Not only do we require the the camera to work but the AOSP camera needs to be fully functional because that's what we ship. We do not ship with any other camera, snapdragon or OEM. This includes but is not limited to having the camera take pictures with both the back camera and front facing camera if applicable and video recording in all definitions.

- The device must have working bluetooth. This includes but is not limited to be transferring files and receive them.

- The device must have working NFC if applicable. This includes but is not limited to being able to beam files and receive them.

- The device must have a working fingerprint scanner if applicable.

- The device must have a working proximity sensor.

- The device must have working WiFi.

- The device must include all device specific and DU overlays. This includes but is not limited to ambient display, LED and hardware keys if applicable.

- The device must not include any unused overlays. This includes but is not limited to packages not being built, obsolete packages or placebo build.prop 'tweaks'.
