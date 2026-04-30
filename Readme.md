# Test Orchestrator

## Introducing the Test-Orchestrator: Your teams digital tester.

This **Test Orchestrator** monitors and maintains the majurity of your automated tests over all 3 layers of the testing pyramid. This agent is based on a mirco-service architecture where specialised agents handle different key factors in the testing flow. With a focus on producing readable output for each action taken and code line written, anyone in the team will understand how this agent has worked. 

### Features
- Analyzes the selected project and creates a test profile
- Identifies the highest-priority test gaps
- Delegates test creation to specialist agents by layer
- Verifies the generated tests with a follow-up analysis pass
- Does not fix any tests that are failing because of source code bugs
- Exports a readable report and status snapshot for the team

### How to use?
- Choose a single project root
- Describe what should be tested
- Confirm the generated test plan
- Let the orchestrator run the specialist agents
- Review the exported report and generated tests

### example prompts
- Generate tests for the backend project
- Analyze frontend test coverage and propose a plan
- Add unit and integration tests for 'folder'
- Create E2E coverage for the 'specific' flow

## Creator's opinion
### Vision
This agent tries to to provide insight in what it does. In my personal opinion people do not know what AI has done for them. This creates a lack of understanding in their code bases what propogates into unmaintainable buggy applications. This Agent maintains documentation on the current testing status of the application and records the things it has done. When required the engineers can read this documentation and quickly get an understanding of what it has done. Aside from understandability this proofs the inmense value of this agent.

In my opinion this agent will be most valuable when in use for a longer time. Setting up the basis requires a bit more calculation power, but once the basis is set it will be more quick to use for newly created files. This is however not something I have been able to test yet. 

### Known downsides

- Currently I feel the agent takes way too long. Especially when you are running it for entire projects it might go on an hour long thinking spree. The quality is high, but I feel like it would be better if faster. I have tried to make it use old documentation of itself in order to speed it up, but I havent been able to test it yet. I also have it limited to at most 3 files per run, so it does not blow itself up.



