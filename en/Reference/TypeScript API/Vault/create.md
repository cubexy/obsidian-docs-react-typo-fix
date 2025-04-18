---
aliases: "Vault.create"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`Vault`](Vault) › [`create`](Vault/create)

## Vault.create() method

Create a new plaintext file inside the vault.

**Signature:**

```typescript
create(path: string, data: string, options?: DataWriteOptions): Promise<TFile>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  <code>path</code> | <code>string</code> | Vault absolute path for the new file, with extension. |
|  <code>data</code> | <code>string</code> | text content for the new file. |
|  <code>options</code> | [`DataWriteOptions`](DataWriteOptions) | _(Optional)_ (Optional) |

**Returns:**

`Promise<`[`TFile`](TFile)`>`

