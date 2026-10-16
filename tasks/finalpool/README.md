# Final Pool

This directory contains all implemented tasks from the BenchTasksCollv3 project.

## Status

As of the latest review, no tasks from the most recent commits have reached the "implemented" status. All new tasks are currently in "implementing" status due to missing `task_config.json` files.

Tasks will be added to this directory as they meet all requirements specified in `tasks/examples/example-task/`.

## Requirements for Implementation

A task is considered "implemented" when it satisfies all requirements:
1. `docs/task.md` - must be non-empty and all English
2. `docs/agent_system_prompt.md` - must be non-empty and all English
3. `docs/user_system_prompt.md` - optional, but if non-empty must be all English
4. `task_config.json` - must have non-empty `needed_mcp_servers` and `needed_local_tools` with `claim_done`
