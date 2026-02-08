# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a proposal templating repository for DevOps/Kubernetes freelance consulting. It helps prepare professional proposals for job applications.

## Mandatory Rules

- NEVER use the em dash character `—` anywhere in proposals or answers. Use `-` or `,` instead.

## Generating Proposals

When user asks "Generate proposal for Thao" or "Generate proposal for Minh":

1. Read `in/job_post.md` to understand the job requirements
2. Read `in/job_questions.md` for screening questions
3. Read the appropriate profile (`profiles/thao_exp.md` or `profiles/minh_exp.md`)
4. Generate proposal using the format in `rule.md`:
   - Create a CONCISE OPENING (2-3 sentences) based on the job post
   - Replace `<CONCISE_OPENING>` placeholder with the generated opening
   - The total proposal must be 800 characters max (including the opening and template)
   - Output to `out/proposal.md`
5. Generate answers for all questions in job_questions.md:
   - Base answers on the profile experience and certifications
   - Make answers specific and relevant to the job post
   - Each answer must be 800 characters max
   - Output to `out/answers.md`

## Key Files

- `rule.md` - Instructions and proposal templates for Thao and Minh
- `profiles/minh_exp.md` - Minh's experience (AWS DevOps Pro, Security Specialty, CKA, CKAD)
- `profiles/thao_exp.md` - Thao's experience (AWS SAP, Google Cloud, Azure, CKA, CKS, CKAD, Golden Kubestronaut)
- `in/job_post.md` - Input: job posting details
- `in/job_questions.md` - Input: screening questions
- `out/proposal.md` - Output: generated proposal
- `out/answers.md` - Output: generated answers
