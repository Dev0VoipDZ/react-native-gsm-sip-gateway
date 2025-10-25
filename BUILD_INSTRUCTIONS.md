# How to Build Your Android APK

## Quick Start - Get Your APK in 3 Steps

### Step 1: Open GitHub Actions
Click this link: https://github.com/Dev0VoipDZ/react-native-gsm-sip-gateway/actions

### Step 2: Find the Latest Build
You should see a list of workflow runs. Look for:
- The most recent one at the top
- It should say "Update GitHub Actions workflow to build APK automatically"
- Status: 🟡 Yellow (running) or ✅ Green (done)

**Click on it!**

### Step 3: Download Your APK
Once the build is complete (shows ✅ green checkmark):
1. Scroll down to the bottom of the page
2. Find the **"Artifacts"** section
3. Click on **"app-debug"** to download
4. Extract the ZIP file
5. You'll get **app-debug.apk** - install this on your phone!

---

## Alternative Method: Merge to Main Branch

If you don't see any workflow runs, merge this branch to main:

1. Go to: https://github.com/Dev0VoipDZ/react-native-gsm-sip-gateway
2. You should see a yellow banner saying "claude/initial-app-setup-011CUU9yb2BeiSXGvcRciMST had recent pushes"
3. Click **"Compare & pull request"**
4. Click **"Create pull request"**
5. Click **"Merge pull request"**
6. The build will start automatically!

---

## What You're Looking For

### On the Actions Page:
```
Actions > All workflows

Recent workflow runs:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🟡 Update GitHub Actions workflow...  #123
   claude/initial-app-setup-011CUU9yb2BeiSXGvcRciMST
   Running now - 2m 34s
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

Click on that row ☝️

### On the Workflow Details Page:
Scroll down to see:
```
Artifacts (files generated)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📦 app-debug          5.2 MB    [Download]
📦 app-release        3.8 MB    [Download]
📦 all-apks          9.0 MB    [Download]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

Click **Download** next to app-debug ☝️

---

## Troubleshooting

### "I don't see any workflow runs"
- The workflow might still be starting (wait 1-2 minutes)
- Or GitHub Actions might be disabled on your repo
- Go to: Settings > Actions > General > Enable "Allow all actions"

### "I see the workflow but it failed"
- Click on the failed workflow
- Click on "build-android" job
- Send me the error message and I'll help fix it

### "I can't access the Actions tab"
- Make sure you're logged into GitHub
- Make sure you're the owner of the repository

---

## Need More Help?

Tell me what you see on this page:
https://github.com/Dev0VoipDZ/react-native-gsm-sip-gateway/actions

Describe:
- Do you see any workflow runs?
- What colors/status do you see?
- Any error messages?
