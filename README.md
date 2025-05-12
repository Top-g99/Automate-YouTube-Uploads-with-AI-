# Automate-YouTube-Uploads-with-AI-
Automate YouTube Uploads with AI-Generated Metadata from Google Drive
Pre‑conditions / Requirements
n8n with Google Drive and YouTube API credentials configured (stored as n8n credentials/variables; no hard‑coded IDs)
Dedicated Google Drive folder for video uploads
YouTube channel with proper upload permissions
AI service access for transcript processing and metadata generation
Sufficient storage for temporary video handling


Setup Instructions
Import this workflow into your n8n instance.
Configure Google Drive credentials; reference folder ID via n8n variable (do not hard‑code).
Set up YouTube API credentials with upload and edit permissions.
Specify the target Google Drive folder ID in the New Video? trigger node (via variable).
Configure AI service credentials for transcript and metadata generation.
Adjust message templates for title, description, and tag creation.
Test with a small video file before production use.

How to Customize
Modify AI prompts to match your channel’s tone and style.
Add conditional logic based on video categories or naming conventions.
Implement notification systems to alert when uploads complete.
Create custom metadata templates for different content types.
Include timestamps or chapter markers based on transcript analysis.
Add social media sharing nodes to announce new uploads.

mportant Notes
Video quality is preserved through the upload process.
Consider YouTube API quotas when handling multiple uploads.
Transcript quality affects metadata generation results.
Videos are initially uploaded without visibility adjustments.
Processing time depends on video length and transcript complexity.
