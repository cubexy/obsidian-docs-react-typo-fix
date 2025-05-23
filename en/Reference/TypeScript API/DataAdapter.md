---
aliases: "DataAdapter"
cssclasses: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`DataAdapter`](DataAdapter)

## DataAdapter interface

Work directly with files and folders inside a vault. If possible prefer using the [Vault](Vault) API over this.

**Signature:**

```typescript
export interface DataAdapter 
```

## Methods

|  Method | Description |
|  --- | --- |
|  [`append(normalizedPath, data, options)`](DataAdapter/append) | Add text to the end of a plaintext file. |
|  [`copy(normalizedPath, normalizedNewPath)`](DataAdapter/copy) | Create a copy of a file. This will fail if there is already a file at <code>normalizedNewPath</code>. |
|  [`exists(normalizedPath, sensitive)`](DataAdapter/exists) | Check if something exists at the given path. For a faster way to synchronously check if a note or attachment is in the vault, use [Vault.getAbstractFileByPath()](Vault/getAbstractFileByPath)<!-- -->. |
|  [`getName()`](DataAdapter/getName) |  |
|  [`getResourcePath(normalizedPath)`](DataAdapter/getResourcePath) | Returns an URI for the browser engine to use, for example to embed an image. |
|  [`list(normalizedPath)`](DataAdapter/list) | Retrieve a list of all files and folders inside the given folder, non-recursive. |
|  [`mkdir(normalizedPath)`](DataAdapter/mkdir) | Create a directory. |
|  [`process(normalizedPath, fn, options)`](DataAdapter/process) | Atomically read, modify, and save the contents of a plaintext file. |
|  [`read(normalizedPath)`](DataAdapter/read) |  |
|  [`readBinary(normalizedPath)`](DataAdapter/readBinary) |  |
|  [`remove(normalizedPath)`](DataAdapter/remove) | Delete a file. |
|  [`rename(normalizedPath, normalizedNewPath)`](DataAdapter/rename) | Rename a file or folder. |
|  [`rmdir(normalizedPath, recursive)`](DataAdapter/rmdir) | Remove a directory. |
|  [`stat(normalizedPath)`](DataAdapter/stat) | Retrieve metadata about the given file/folder. |
|  [`trashLocal(normalizedPath)`](DataAdapter/trashLocal) | Move to local trash. Files will be moved into the <code>.trash</code> folder at the root of the vault. |
|  [`trashSystem(normalizedPath)`](DataAdapter/trashSystem) | Try moving to system trash. |
|  [`write(normalizedPath, data, options)`](DataAdapter/write) | Write to a plaintext file. If the file exists its content will be overwritten, otherwise the file will be created. |
|  [`writeBinary(normalizedPath, data, options)`](DataAdapter/writeBinary) | Write to a binary file. If the file exists its content will be overwritten, otherwise the file will be created. |

