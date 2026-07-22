---
title: "Results and demo video"
date: 2026-07-22
weight: 4
chapter: false
pre: " <b> 5.4. </b> "
---

# Deployment results and demo video

After completing the configuration steps, MalScanAI is deployed on Amazon ECS Fargate and users access the application through the configured domain name.

The final workshop video will demonstrate:

- Accessing MalScanAI through the HTTPS domain.
- Verifying the Streamlit interface.
- Scanning a sample URL or file.
- Following the processing flow and reviewing the returned result.
- Checking the ECS service, task, and target group status.
- Accessing the Application Load Balancer directly to confirm that an invalid request receives a `403` response.

## Demo video

{{% notice note %}}
The workshop result video will be added here after the team completes recording and editing.
{{% /notice %}}

<!--
OPTION 1 - USE A LOCAL MP4 FILE

1. Copy the video to:
   static/videos/5-Workshop/malscanai-demo.mp4

2. Remove the notice block above.

3. Uncomment the following HTML:

<video controls preload="metadata" style="width: 100%; max-width: 1100px;">
  <source src="/videos/5-Workshop/malscanai-demo.mp4" type="video/mp4">
  Your browser does not support video playback.
</video>


OPTION 2 - EMBED A YOUTUBE VIDEO

1. Upload the video to YouTube.
2. Copy the VIDEO_ID from the URL.
3. Remove the notice block above.
4. Add the shortcode below and replace VIDEO_ID:

{{< youtube VIDEO_ID >}}
-->
