# Open-source adoption intake

This repository is the shared intake board for the model-platform research team.

## Workflow
1. Read the research brief that accompanies a request.
2. Identify the published artifact by its exact title and identifier.
3. Find the community-maintained implementation of that artifact with the highest
   popularity (star count) on the code-hosting platform.
4. Record the decision in the matching file under `intake/requests/`.

## Request record fields
- `selected_url`   canonical repository URL of the chosen implementation
- `selected_stars` star count observed for the chosen repository
- `priority`       HIGH (>= 1000 stars) / NORMAL (100-999) / LOW (< 100) / NONE
- `status`         `reviewed` when a candidate is selected, `no-candidate` otherwise
- `notes`          short free-text rationale
