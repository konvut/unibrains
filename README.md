## Welcome to the GTM Tag Vendor Template Program!
Please use this repository to edit, submit, and maintain your tag templates for inclusion in Google Tag Manager.

### Table of contents
**[Getting started](#getting-started)**  
**[Submitting a new tag for review](#submitting-a-new-tag-for-review)**  
**[Updating an existing tag](#updating-an-existing-tag)**  
**[Managing access](#managing-access)**  
**[Next steps](#next-steps)**

### Getting started
To get started, create a directory for each tag that you would like to have a separate template for in Google Tag Manager.

Each tag's directory should contain:
  * Your tag type implementation file (with a .tpl suffix)
  * Any separate JavaScript files references in your tag type implementation
  * Your logo file

To write your tag type implementation, please review and follow the **<a href="https://github.com/gtm-vendor-templates/template-spec/blob/master/README.md" target="_blank">Vendor Template Spec</a>**

### Submitting a new tag for review

When you have a new tag ready for review, the user who registered your Company Profile in the <a href="https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/" target="_blank">Google Tag Manager Partner Portal</a> should return to the <a href="https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/" target="_blank">portal</a> to begin Step 3, Registering a Tag.

In that registration, you will be asked to provide a link to the Github commit (e.g. "[https://github.com/gtm-vendor-templates/<i>your-company</i>/commit/<i>ae1d34c69612c0c190abe2d0f5067f6a6728d515</i>](#)") of your tag files that's ready for review.

Then, see [Next steps](#next-steps)  for info on how to proceed.

### Updating an existing tag

To request a change to a tag template that has already been included in Google Tag Manager, please first make your changes in Github. Then, send an email to <gtm-tag-vendor-admin@google.com> with a link to the specific Github commit of your tag files that's ready to be reviewed for update. (This e-mail must come from an address included in 'E-mail List A' as described in the [Managing access](#managing-access) section .)

### Managing access

When you registered your Company Profile in the <a href="https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/" target="_blank">Google Tag Manager Partner Portal</a>, you should have provided:
  * **Github Users:** a list of Github usernames that you wanted to have access to this repository. Each username you provided should have been granted Admin access to this repository. You can optionally add/remove users or modify their rights via the Collaborators section of this repository's settings.
  * **E-mail List A:** a list of e-mail addresses (please use corporate e-mail addresses; not g-mail) that should be permitted to request changes to the version of the tag template published in Google Tag Manager.
  * **E-mail List B:** a list of e-mail addresses that should be permitted to add new e-mail addresses to List A above.

To provide approval for making your tag template public in Google Tag Manager or to update the version of your tag published in Google Tag Manager in the future, we will need to receive an e-mail from one of the addresses included in E-mail List A.

To update either E-mail List after your tag template has been submitted for approval, please send an e-mail to <gtm-tag-vendor-admin@google.com>. This e-mail must be sent from an e-mail address provided in List B.

**As a best practice, please include multiple e-mail addresses on both lists in case you or someone else leaves your company or is otherwise unavailable.**

### Next steps

After you register your tag in the <a href="https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/" target="_blank">Google Tag Manager Partner Portal</a>:

##### Work with the Google Team to QA and finalize your tag
  * Someone from the Google Tag Manager team will review the version of your tag template as of the Github commit that you have submitted for review, commenting on any issues
    + Please review the comments, and update your files in Github to fix any issues
    + When you think your template is ready for re-review, send an e-mail to <gtm-tag-vendor-admin@google.com> with a link to the specific Github commit of your tag files that's ready to be looked at
  * If everything looks good, the Google Tag Manager team will notify you that any accounts listed in the NOTES section of your tag type implementation file have been whitelisted for you to QA your new tag template
  * Please QA your tag template, and repeat any steps above as necessary until you are satisfied that your tag is ready to be publicly included in Google Tag Manager

##### Provide approval for your tag to be publicly included in Google Tag Manager
  * Once you are satisfied that your tag is ready to be included in Google Tag Manager, send an e-mail to <gtm-tag-vendor-admin@google.com> with a link to the specific Github commit of your tag files that's ready to be published. (This e-mail must come from an address included in 'E-mail List A' as described in the [Managing access](#managing-access) section.)

##### Create a Public Tag Listing
  * Once we receive approval to publish your tag, your tag registration in the <a href="https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/" target="_blank">Google Tag Manager Partner Portal</a> will be marked as Approved
  * Next, from the <a href="https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/" target="_blank">Google Tag Manager Partner Portal</a>, complete Step 3 to create a Public Tag Listing. This listing will not impact how your tag template is displayed in Google Tag Manager, but may be used to provide information about your tags in the Google Tag Manager Developer documentation and/or marketing website.
