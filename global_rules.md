I am eager to see you working and showing your best outcome, and it's better to ask for forgiveness than permission. So PLEASE just try your best. As long as you judge the command won't destroy data, you can try. Make sure you REALLY did everything you wanted before returning the command prompt to the me, the user. That said, you should also consider that the best development is iterative development. So we should implement, test (by deploying or whatever), committing, update documentation, and start again!

When performing investigative tasks, repeat what you understood about the issue/feature and then proceed with the investigation/implementation.

When creating new projects, SUGGEST FIRST what language this will be developed, if not explicitly specified. 

Make sure there are plenty of logs to understand what's going on on the app, when coding! Logs are better removed after the app is deployed and working than added when things go wrong!

When creating new projects that require npm or node, check the running node version, create a .nvmrc file in the directory.

When creating new projects that require cdk, check the running cdk version, create a .cdkrc file in the directory. We always want to use CDK V2.

When creating new projects that require python, check the running python version, create a .python-version file in the directory. We also always want to use pip and venv, with the venv directory being called .venv.

When creating new projects that require java, check the running java version, create a .java-version file in the directory, or the equivalent that would work with jenv.

Always keep README.md files updated with changes before we commit.

Always inspect the local staged and unstaged changes when you commit. There may be files you're not aware of; always ask for confirmation before commiting.

When exporting knowledge, you are an expert research compiler. Based on the current findings in this workspace/project, generate a BrainLift DOK summary using the structure below. Include only well-sourced and meaningful content. Classify each insight, opinion, fact, or summary at the correct DOK level. Fill in all sections with relevant information when available. When exporting links to files, use GitHub permalinks instead of local files. Store all brainlifts in /Users/lmrlima/dev/brainlifts; set the file name to the repo you're working on. Add to existing files instead of creating new files, if possible. Example format:

```markdown
- DOK3 - Insights
  - [Insight 1 – patterns, non-obvious conclusions, or model-level deductions]
  - [Insight 2]
  - [Insight 3]
  - [Insight 4]
- DOK2 - Knowledge Tree
  - [Category 1]
    - [Source 1: title or link]
      - DOK1 - facts
        - [Simple, verifiable fact 1]
        - [Fact 2]
        - [Fact 3]
      - DOK2 - summary
        - [Synthesized summary or interpretation]
        - [Another key takeaway]
      - link to source: [URL or reference]
  - [Category 2]
    - [Subcategory 2.1]
      - [Source 2]
        - DOK1 - facts
          - [Fact 1]
          - [Fact 2]
        - DOK2 - summary
          - [Summary point 1]
          - [Summary point 2 – supports SPOV]
          - [Summary point 3 – contradicts SPOV]
        - link to source: [URL or reference]
    - [Subcategory 2.2]
      - [Source 3]
        - DOK1 - facts
          - [Fact 1]
          - [Fact 2]
          - [Fact 3]
        - DOK2 - summary
          - [Summary point 1 – supports SPOV]
          - [Summary point 2]
        - link to source: [URL or reference]
```
