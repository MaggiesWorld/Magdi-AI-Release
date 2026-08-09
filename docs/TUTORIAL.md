# Quick Tutorial

## Prerequisites

One of the following AI providers is required:
- OpenAI
- Anthropic

## Step 1 - Install Magdi-AI

Download 'install-magdi-ai.exe' and run the installation program.

Choose your desired provider, model and destination directory.

Run magdi-ai.exe to start the system.

Follow the instructions in the command window for:

- Magdi-AI URL
- Administrator username
- Administrator password

## Step 2 - Login

Login using the administrator account created during installation.

You'll be asked to change your password after your first login.

---

## Step 3 - Onboarding

Complete onboarding by telling the Orchestrator:

**Let's onboard.**

Magdi-AI will learn how you work, your preferred technology stack, and your QA preferences, then configure your QA environment.

---

## Step 4 - Create Project

Create your first project using the Orchestrator.

For example:

**Create a new project called Evolution.**

---

## Step 5 - Add a Work Item

Open **QA Flow**.

Click **+** to create your first Work Item and save it.

---

## Step 6 - Start the Workflow

Open the saved Work Item and click **Ready**.

The Quality Workflow Engine (QWE) will process the Work Item according to your configured workflow.

As the Work Item progresses, Magdi-AI automatically performs configured activities and creates QA artifacts.

---

## Step 7 - Review the Work Item

When QWE moves the Work Item to **Review**, review the generated artifacts using **Resources**.

- **Approve** the Work Item when you're satisfied with the results.
- **Reject** the Work Item with additional instructions when changes are needed.

QWE will take it from there.

---

You're ready to explore Magdi-AI!

---

# Known Issues

## Duplicating Work Items

Moving a newly created Work Item before explicitly saving it may cause the Work Item to appear twice in the Backlog.

### Workaround

1. Click **+** to add a Work Item.
2. Click **Save**.
3. Open the saved Work Item.
4. Click **Ready**.

QWE will process the Work Item and notify you when it is ready for review.

---

You're ready to explore Magdi-AI.

---

## Known Issues

### Duplicating Work Items

If you add a work item and click ready before saving, the item will save and duplicate.

Work Around
1.  Click '+' to Add Work Item
2.  Click Save
3.  When ready, Click Work Item
4.  Click 'Ready'

The QWE will take it from there and alert you when the item is ready for review.


### Workflows

Currently, only Kanban-QA is supported.  The other workflows will be available after the beta release.