---
ms.technology: devops-agile
ms.prod: devops
ms.author: kaelli
author: KathrynEE
ms.topic: include
ms.date: 07/09/2020
---

<a id="discussion" />

::: moniker range=">= tfs-2017" 

## Capture comments in the Discussion section 

Use the **Discussion** section to add and review comments made about the work being performed. 

> [!div class="mx-imgBorder"]  
> ![Discussion section within a work item form](/azure/devops/boards/backlogs/media/discussion-section.png)   

::: moniker-end 

::: moniker range=">= azure-devops-2019"

The rich text editor tool bar displays below the text entry area when you click your cursor within each text box that can be formatted. 

> [!div class="mx-imgBorder"]  
> ![Discussion section, New Rich Text Editor toolbar](/azure/devops/boards/queries/media/share-plans/discussion-rich-text-editor-toolbar.png)  

### Mention someone, a group, work item, or pull request (![ ](/azure/devops/media/icons/at-mention.png), ![ ](/azure/devops/media/icons/work-id.png), or ![pull-request id icon](/azure/devops/media/icons/pr-id.png))

Choose one of these icons &mdash;![ ](/azure/devops/media/icons/at-mention.png), ![ ](/azure/devops/media/icons/work-id.png), or ![pull-request id icon](/azure/devops/media/icons/pr-id.png)&mdash; to open a menu of recent entries you've made to mention someone, link to a work item, or link to a pull request. Or, you can simply type <strong>@</strong>, <strong>#</strong>, or <strong>!</strong> to open the same menu.   

> [!div class="mx-imgBorder"]  
> ![Discussion section, @mention drop-down menu](/azure/devops/boards/media/discussion-at-mention.png)  

::: moniker-end

::: moniker range="azure-devops-2019"  

> [!NOTE]   
> This latest version of the rich text editor requires Azure DevOps Server 2019 Update 1 or later version. 

::: moniker-end

::: moniker range=">= azure-devops-2019"  

Type a name, or enter a number and the menu list will filter to match your entry. Choose the entry you want to add. You can bring a group into the discussion by typing **@** and the group name, such as a team or security group. 

### Edit or delete a comment 

If you need to edit or delete any of your discussion comments, choose ![ ](/azure/devops/media/icons/edit.png) <strong>Edit</strong> or choose the ![ ](/azure/devops/media/icons/actions-icon.png) actions icon and then choose **Delete**. 

> [!div class="mx-imgBorder"]  
> ![Discussion section, Edit, Delete actions](/azure/devops/boards/media/discussion-edit-delete.png)  

::: moniker-end

::: moniker range="azure-devops-2019"  

> [!NOTE]   
> The edit/delete feature requires Azure DevOps Server 2019 Update 1 or later version. 

::: moniker-end

::: moniker range=">= azure-devops-2019"  

After updating the comment, choose **Update**. To delete the comment, you'll need to confirm that you want to delete it. 

A full audit trail of all  edited and deleted comments is maintained in the **History** tab on the work item form. 

::: moniker-end  

::: moniker range=">= tfs-2017 <= tfs-2018" 

Use the [**@mention** control](/azure/devops/notifications/at-mentions) to notify another team member about the discussion. Simply type **@** and their name. To reference a work item, use the [**#ID** control](/azure/devops/notifications/add-links-to-work-items). Type **#** and a list of work items that you've recently referenced will appear from which you can select.  

To reference a work item, use the **#ID** control. Type **#** and a list of work items that you've recently referenced will appear from which you can select.  

Note that you can't edit or delete comments once they've been entered. 

::: moniker-end 

::: moniker range=">= tfs-2017 <= azure-devops-2020" 

> [!IMPORTANT]  
> For on-premises Azure DevOps Server, [you must configure an SMTP server](/azure/devops/server/admin/setup-customize-alerts) in order for team members to receive notifications.

::: moniker-end 

::: moniker range=">= azure-devops-2020"

### Add a reaction to a comment 

You can add one or more reactions to any comment. Choose a smiley icon at the upper-right corner of any comment or choose from the icons at the bottom of a comment next to any existing reactions. To remove your reaction, click the reaction on the bottom of your comment. The following shows an example of the experience of adding a reaction, as well as the display of reactions on a comment.

> [!div class="mx-imgBorder"]  
> ![Add reactions to a comment](/azure/devops/release-notes/2019/media/156_09.png)  

::: moniker-end 
