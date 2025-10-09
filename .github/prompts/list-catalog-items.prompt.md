---
mode: agent
model: Claude Sonnet 4
tools: ['githubRepo', 'get_file_contents']
description: 'Generate comprehensive test cases from acceptance criteria with automation guidance'
---

You are to retrieve the possible pre configured IaC catalog templates from our central Catalog Repo at "https://github.com/DevExpGbb/devcenter-catalog".

Retrive the list of items found in the catlog directory at ```%repo-root%/Environment-Definitions/ARMTemplates``` in that repo.

If the user specifies a particular type of service, narrow down the list to only include items that match that type.