## Welcome to the GTM Tag Vendor Template Program!
Please use this repository to edit, submit, and maintain your tag templates for inclusion in Google Tag Manager.

### Table of contents
**[Getting started](#getting-started)**  
**[Submitting your tag for review](#submitting-your-tag-for-review)**  
**[Updating an existing tag](#updating-an-existing-tag)**  
**[Next steps](#next-steps)**

### Getting started
To get started, create a directory for each tag that you would like to have a separate template for in Google Tag Manager.

Each tag's directory should contain:
  * Your tag type implementation file (with a .tpl suffix)
  * Any separate JavaScript files references in your tag type implementation
  * Your logo file

To write your tag type implementation, please review and follow the **[Vendor Template Spec](https://github.com/gtm-vendor-templates/template-spec/blob/master/README.md)**

### Submitting your tag for review

When your tag template is ready for review, the user who registered your Company Profile in the [Google Tag Manager Partner Portal](https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/) should return to the [portal](https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/) to begin Step 3, Registering a Tag.

In that registration, you will be asked to provide a link to the Github version of your tag that's ready for review, as well as to provide:
  * **List A:** a list of e-mail addresses (please use corporate e-mail addresses; not g-mail) that should be permitted to request changes to the version of the tag template published in Google Tag Manager
  * **List B:** a list of e-mail addresses that should be permitted to add new e-mail addresses to List A above

Should you need to make a change to the version of your tag template published in Google Tag Manager in the future, we will need to receive an e-mail from one of the addresses included in List A.

To update either list after your tag template has been submitted for approval, please send an e-mail to <gtm-tag-vendor-admin@google.com>. This e-mail must be sent from an e-mail address provided in List B.

As a best practice, please include multiple e-mail addresses on both lists in case you or someone else leaves your company or is otherwise unavailable.

### Updating an existing tag

To request a change to a tag template that has already been included in Google Tag Manager, please first make your changes in Github. Then, send an email to <gtm-tag-vendor-admin@google.com> with a link to the specific version of your tag that's ready to be reviewed for update.

### Next steps

After you register your tag in the [Google Tag Manager Partner Portal](https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/):

##### Work with the Google Team to QA and finalize your tag
  * Someone from the Google Tag Manager team will review the version of your template in Github that you have submitted for review, indicating whether there are any issues
    + Update your files in Github to fix any issues
    + When you think your template is ready for re-review, send an e-mail to <gtm-tag-vendor-admin@google.com> with a link to the specific version of your tag in Github that's ready
  * If everything looks good, the Google Tag Manager team will notify you that any accounts listed in the NOTES section of your tag type implementation file have been whitelisted for you to QA your new tag template
  * Please QA your tag template, and repeat any steps above as necessary until you are satisfied that your tag is ready to be publicly included in Google Tag Manager

##### Provide approval for your tag to be publicly included in Google Tag Manager
  * Once you are satisfied that your tag is ready to be included in Google Tag Manager, send an e-mail to <gtm-tag-vendor-admin@google.com> with a link to the specific version of your tag in Github that's ready to be published (this email must come from an e-mail address provided in List A (as described in "Submitting Your Tag for Review" above)

##### Create a Public Tag Listing
  * Once we receive approval to publish your tag, your tag registration in the [Google Tag Manager Partner Portal](https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/) will be marked as Approved
  * Next, from the [Google Tag Manager Partner Portal](https://gtm-partner-gallery.appspot.com/tagmanager/partners/owner/profile/company/), complete Step 3 to create a Public Tag Listing. This listing will not impact how your tag template is displayed in Google Tag Manager, but may be used to provide information about your tags in the Google Tag Manager Developer documentation and/or marketing website.
