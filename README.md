# Windsurf and Cursor Docs_Templates

## Setup

1. Create the venv for python
```sh
python -m .venv venv
```

2. Install Rich for the Directory Tree
```sh
pip install rich
```

3. Prompt the agent to generate code implementations for the System Documents

```
1. Review the [@.cursorrules](@.windsurfrules) file in full, this is the core of your new comprehensive workflow. It **MUST** be adhered to during the CodeBase Restructuring.
2. Begin setting up `System Documents` with proper context from the CodeBase. The Core files you will be using as the AI Developer are: @CodeBase_Docs/System_Integration.md and @CodeBase_Docs/System_Architecture.md .
3. Review the `System Documents` and being providing the proper context to ensure the files are using the code base specifications. Currently they are general specifications, they need to be updated with the CodeBase Context. **DO NOT** Remove any of these workflows, only implement them with our CodeBase for smooth transition and graceful handling with future implementations.
```

## Ongoing Prompting Upkeep

```
1. Review the [@.cursorrules](@.windsurfrules) file, you must adhere to the strict workflow to ensure CodeBase consistency. Ensure you are updating and reviewing the `Cursor System Documents` and seeking Context in the `Codebase Context Documents`
2. Continue to the next Task on the [`Scratchpad`](`System_Scratchpad`)
```