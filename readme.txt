Name: Awaiting Activation Count
Description: Shows the number of users awaiting activation in the header.
Website: http://mattrogowski.co.uk
Author: MattRogowski
Authorsite: http://mattrogowski.co.uk
Version: 1.6.4
Compatibility: 1.6.x
Files: 2
Templates added: 1
Template changes: 1

To Install:
Upload ./inc/plugins/aacount.php to ./inc/plugins/
Upload ./inc/languages/english/aacount.lang.php to ./inc/languages/english/
Go to ACP > Plugins > Activate

Information:
This plugin will add a box to the header telling you if there are users awaiting activation.

It only shows if you have ACP access, if admin/email activation is turned on, and if there is 1 or more user awaiting activation.

Clicking the message takes you to the ACP page with all the users awaiting activation.

Change Log:
18/07/09 - v0.1 -> Initial 'beta' release.
03/09/09 - v0.1 -> v1.0 -> To upgrade, just upload the new file over the current one, no need to deactivate.
01/09/10 - v10. -> v1.6 -> Rewritten, file name changed. 1.6 compatible only.
23/10/10 - v1.6 -> v1.6.1 -> Will now recount the number of users awaiting activation when you use the inline mass activate feature, or edit a user's usergroup from the awaiting activation group to something else. To upgrade, reupload ./inc/plugins/aacount.php.
07/11/10 - v1.6.1 -> v1.6.2 -> Wouldn't recount properly when using mass activation. To upgrade, reupload ./inc/plugins/aacount.php.
07/11/10 - v1.6.2 -> v1.6.3 -> Now has an option to rebuild the cache of number of users awaiting activation in the Cache Manager in the Tools and Maintenance section of the ACP. To upgrade, reupload ./inc/plugins/aacount.php.
20/11/10 - v1.6.3 -> v1.6.4 -> Fixed a bug where it wouldn't recount the number when deleting a user. Also now recounts when you add and merge users. To upgrade, reupload ./inc/plugins/aacount.php.

Copyright 2010 Matthew Rogowski

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at

 ** http://www.apache.org/licenses/LICENSE-2.0

 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.