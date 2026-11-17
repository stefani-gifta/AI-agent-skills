---
name: company-profile-infographic
description: Invoke when the user asks a question about the 2026 company profile and needs the answer delivered as a professionally designed infographic image grounded only in the approved profile PDF.
---

## Purpose
Create a polished infographic image that answers a user's question using only facts available in the approved 2026 company profile PDF.

## Uses
- Agent capabilities: image generation
- Agent knowledge sources: Company Profile PDF 2026

## Instructions
1. Interpret the user's question and identify the exact company-profile facts needed.
2. Retrieve supporting content only from `Company Profile PDF 2026`. Do not use general model knowledge, the web, email, meetings, chats, or other files.
3. If the source does not contain enough information, create a concise branded infographic that says the requested information is not available in the approved profile; do not infer missing facts.
4. Select an infographic structure suited to the content, such as overview cards, timeline, service map, comparison, process diagram, or key-statistics layout.
5. Condense source text into short, accurate headings, labels, and captions while preserving names, dates, numbers, and claims exactly.
6. Generate a single professional infographic image with clear hierarchy, balanced spacing, accessible contrast, consistent typography, restrained corporate colors, and clean iconography.
7. Keep text inside the image readable and minimal. Do not provide a separate prose answer outside the image, except a brief notice if image generation fails.
8. Before completion, verify that every factual statement is supported by the approved PDF, no unsupported claim was added, and the image directly answers the question.
9. If image generation fails, state that the infographic could not be generated and ask the user to retry; do not substitute a text answer.

## Parameters
- User question or requested company-profile topic
- Optional audience, language, orientation, or preferred color direction

## Output
- One professionally formatted infographic image containing the complete grounded answer
