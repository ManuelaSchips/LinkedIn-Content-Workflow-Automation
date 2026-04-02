# User Guide

This guide explains how to use the LinkedIn Ad-hoc Posting Workflow for creating and reviewing AI-generated LinkedIn carousel drafts.

The workflow was designed to make LinkedIn content creation faster, more consistent, and easier to manage.

---

## Purpose

The workflow helps generate role-specific LinkedIn carousel drafts based on a topic entered in SharePoint.

It supports:

- structured topic intake
- automated role-based matching
- AI-generated draft creation
- human review before publishing

---

## Step 1: Create a New Topic Request

Open the **LinkedIn Ad-hoc Requests** SharePoint list.

Add a new item and fill in the relevant fields:

- **Title**  
  Enter the topic of the LinkedIn post.

- **Context Link** *(optional)*  
  Add a link if the workflow should use information from a specific page as additional context.

- **Context Note** *(optional)*  
  Add a short note if there is a specific angle, message, or detail that should be considered.

- **Language**  
  Select the language in which the LinkedIn post should be generated.

You do **not** need to change the request status manually.  
When the item is saved, the status is handled automatically so the workflow can process it correctly.

Save the item once all relevant information has been entered.

---

## Step 2: Wait for the Workflow to Run

The workflow runs automatically every full hour.

During execution, it will:

1. check the request list for new topics
2. match each topic with the most relevant job roles
3. generate LinkedIn carousel drafts for each relevant role
4. store the generated drafts in the content list
5. update the request status to **Draft**

Once the request status changes to **Draft**, the topic has already been processed by the workflow and will not be picked up again unless the status is manually reset.

---

## Step 3: Review Generated Content

When content is ready for review, open the **LinkedIn Ad-hoc Content** SharePoint list.

Filter the **Content Status** column by **Review**.

This will show all generated drafts that are waiting to be checked.

Each entry contains a generated LinkedIn post draft for a specific job role.

---

## Step 4: Copy and Use the Draft

Open the draft you want to review.

In the field **Generated Post**, select the text and copy it.

You can then paste the draft into your LinkedIn post template.

If needed, make small edits before publishing to ensure the final quality and tone are appropriate.

---

## Step 5: Update the Content Status

After checking the draft, update the status accordingly:

- **Published**  
  Use this status after the post has been published on LinkedIn.

- **Rejected**  
  Use this status if the generated draft should not be used.

This helps keep the content process transparent and avoids repeated review of the same item.

---

## Notes

- The workflow creates **drafts**, not final published posts.
- Human review is required before publishing.
- Topics can be created in different languages, and the output language is controlled through the selected language field.
- Optional context links and notes can improve the relevance of the generated output.

---

## Summary

The workflow enables a structured content process:

- enter a topic
- let the workflow generate role-specific carousel drafts
- review the output
- publish or reject the content
- keep the workflow status clean and trackable

This makes LinkedIn content production more scalable while keeping editorial control in human hands.
