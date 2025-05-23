---
aliases: "FuzzySuggestModal"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`FuzzySuggestModal`](FuzzySuggestModal)

## FuzzySuggestModal class


**Signature:**

```typescript
export abstract class FuzzySuggestModal<T> extends SuggestModal<FuzzyMatch<T>> 
```
**Extends:** [`SuggestModal`](SuggestModal)`<`[`FuzzyMatch`](FuzzyMatch)`<T>>`

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [`(constructor)(app)`](SuggestModal/(constructor).md) |  | <p>Constructs a new instance of the <code>SuggestModal</code> class</p><p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [`app`](Modal/app) |  | [`App`](App) | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`containerEl`](Modal/containerEl) |  | <code>HTMLElement</code> | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`contentEl`](Modal/contentEl) |  | <code>HTMLElement</code> | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`emptyStateText`](SuggestModal/emptyStateText) |  | <code>string</code> | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`inputEl`](SuggestModal/inputEl) |  | <code>HTMLInputElement</code> | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`limit`](SuggestModal/limit) |  | <code>number</code> | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`modalEl`](Modal/modalEl) |  | <code>HTMLElement</code> | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`resultContainerEl`](SuggestModal/resultContainerEl) |  | <code>HTMLElement</code> | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`scope`](Modal/scope) |  | [`Scope`](Scope) | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`shouldRestoreSelection`](Modal/shouldRestoreSelection) |  | <code>boolean</code> | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`titleEl`](Modal/titleEl) |  | <code>HTMLElement</code> | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [`close()`](Modal/close) |  | <p>Hide the modal.</p><p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`getItems()`](FuzzySuggestModal/getItems) | <code>abstract</code> |  |
|  [`getItemText(item)`](FuzzySuggestModal/getItemText) | <code>abstract</code> |  |
|  [`getSuggestions(query)`](FuzzySuggestModal/getSuggestions) |  |  |
|  [`onChooseItem(item, evt)`](FuzzySuggestModal/onChooseItem) | <code>abstract</code> |  |
|  [`onChooseSuggestion(item, evt)`](FuzzySuggestModal/onChooseSuggestion) |  |  |
|  [`onClose()`](Modal/onClose) |  | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`onNoSuggestion()`](SuggestModal/onNoSuggestion) |  | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`onOpen()`](Modal/onOpen) |  | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`open()`](Modal/open) |  | <p>Show the modal on the the active window. On mobile, the modal will animate on screen.</p><p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`renderSuggestion(item, el)`](FuzzySuggestModal/renderSuggestion) |  |  |
|  [`selectActiveSuggestion(evt)`](SuggestModal/selectActiveSuggestion) |  | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`selectSuggestion(value, evt)`](SuggestModal/selectSuggestion) |  | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`setContent(content)`](Modal/setContent) |  | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |
|  [`setInstructions(instructions)`](SuggestModal/setInstructions) |  | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`setPlaceholder(placeholder)`](SuggestModal/setPlaceholder) |  | <p>(Inherited from [SuggestModal](SuggestModal)<!-- -->)</p> |
|  [`setTitle(title)`](Modal/setTitle) |  | <p>(Inherited from [Modal](Modal)<!-- -->)</p> |

