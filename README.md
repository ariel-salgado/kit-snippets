# kit-snippets

The extension provides snippets for various patterns in SvelteKit and Svelte. KitSnippets have:

- Components
- Logic Blocks
- Endpoints
- Load Functions
- Error Handlings
- And More...

## Snippets

Kit-snippets provides snippets for both Svelte and Sveltekit!

#### Svelte snippets

| Snippet         | Output                                              |
| --------------- | --------------------------------------------------- |
| kitComp         | Scaffolds a Svelte component                        |
| kitCompTs       | Scaffolds a TypeScript Svelte component             |
| kitCompPost     | Scaffolds a PostCSS Svelte component                |
| kitCompTSPost   | Scaffolds a Typescript & PostCSS Svelte component   |
| kitModule       | Create a module script tag                          |
| kitModuleTs     | Create a Typescript module script tag               |
| kitSlotProp     | Create a slot with props                            |
| kitStylePost    | Create a PostCSS style tag                          |
| kitIf           | Create a Svelte `{#if}` block                       |
| kitIfElse       | Create a Svelte `{#if} {:else}` block               |
| kitEach         | Create a Svelte `{#each}` block                     |
| kitEachIdx      | Create a Svelte `{#each index}` block               |
| kitEachElse     | Create a Svelte `{#each} {:else}` block             |
| kitAwait        | Create a Svelte `{#await}` block                    |
| kitKey          | Create a Svelte `{#key}` block                      |
| kit:component   | Create a `<svelte:component />` tag                 |
| kit:element     | Create a `<svelte:element />` tag                   |
| kit:window      | Create a `<svelte:window />` tag                    |
| kit:body        | Create a `<svelte:body />` tag                      |
| kit:head        | Create a title and description in the document head |
| kit:options     | Create a `<svelte:options />` tag                   |
| kit:fragment    | Create a `<svelte:fragment />` tag                  |
| kitOnMount      | Scaffolds a `onMount` method                        |
| kitBeforeUpdate | Scaffolds a `beforeUpdate` method                   |
| kitAfterUpdate  | Scaffolds a `afterUpdate` method                    |
| kitOnDestroy    | Scaffolds a `onDestroy` method                      |
| kitDispatcher   | Scaffolds a `createEventDispacther` object          |

#### SvelteKit Snippets

| Snippet           | Output                                                              |
| ----------------- | ------------------------------------------------------------------- |
| kitPageData       | Scaffolds a SvelteKit PageData assignment                           |
| kitPageDataTS     | Scaffolds a TypeScript SvelteKit PageData assignment                |
| kitActionData     | Scaffolds a SvelteKit ActionData assignment                         |
| kitActionDataTS   | Scaffolds a TypeScript SvelteKit ActionData assignment              |
| kitPageAction     | Scaffolds a SvelteKit PageData and ActionData assignment            |
| kitPageActionTS   | Scaffolds a TypeScript SvelteKit PageData and ActionData assignment |
| kitError          | Scaffolds a `+error.svelte` template                                |
| kitLoadTS         | Scaffolds a TypeScript SvelteKit LoadData function                  |
| kitEndpointTS     | Scaffolds a TypeScript SvelteKit Endpoint function                  |
| kitActionsTS      | Scaffolds a TypeScript SvelteKit Actions function                   |
| kitHandle         | Scaffolds a SvelteKit Handle function                               |
| kitHandleTS       | Scaffolds a TypesCript SvelteKit Handle function                    |
| kitFetch          | Scaffolds a SvelteKit HandleFetch function                          |
| kitFetchTS        | Scaffolds a TypesCript SvelteKit HandleFetch function               |
| kitClientError    | Scaffolds a SvelteKit HandleClientError function                    |
| kitClientErrorTS  | Scaffolds a Typescript SvelteKit HandleClientError function         |
| kitServerError    | Scaffolds a SvelteKit HandleServerError function                    |
| kitServerErrorTS  | Scaffolds a TypeScript SvelteKit HandleServerError function         |
| kitParamMatcherTS | Scaffolds a TypeScript SvelteKit ParamMatcher function              |
| kitEnhancedForm   | Scaffolds a Sveltekit Enhanced form                                 |

## Why some snippets doesn't have a JS version?

Some snippets like `kitLoadTS` and `kitActionsTS` doesn't have a JS version because they are supported by [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode) and if you don't have that extension installed, you should.

## Issues and Improvements

Issues and improvements are welcome!
Please describe the issues as best as you can and same for improvements.
