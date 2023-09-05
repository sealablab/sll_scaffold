---
aliases
ctime: 2023-09-04
mtime: 2023-09-04-22-30
---

# 00_Vault_Hierarchy
[[00_Vault_Hierarchy]] Okay. Lets get started.  Directories, tags, timestamps and more

## Timestamps
YYYY-MM-DD-hh-mm : (mtime)
YYYY-MM-DD : (ctime)

## Tags vs Folders
I’m not going to pretend to have any novel insights to contribute into the ongoing tabs-vs-spaces debate of our current decade, but I will point out the following:
### Folders
Folders are inherently hierarchical and exclusionary. (//at least, before symlinks come into being)
As a computer programmer this maps nicely to the mental model of object-hierarchy common in C++ and other OO Programming language.

The folder structure of this vault is designed to be a one-to-one mapping between certain datatypes.

For example, a note within the `/People` TLD (Top Level Directory) will (or at least *should*) always be defined by the
'Person' [[FileClass]]

Similarly, a note inside `/Lab/Consumables` should be of FileClass `Lab/Consumable`

### Tags 
Tags are left entirely up to the reader. The only assumption the vault makes about tags is that they will be stored in a 'tags' metadata field


# top level folders
With that little explainer out of the way, let me describe the few top level directories present at this vaults genesis


## Root/
| —   | —   |
| --- | --- |
| [[/People]]    |     |

## Lab/

| —                     | —                                                       | -                                             |     |     |
| --------------------- | ------------------------------------------------------- | --------------------------------------------- | --- | --- |
| Folder                | Use                                                     | metadata                                      |     |     |
| -                     | —                                                       | -                                             |     |     |
| [[Lab/Equipment]]     | status over lab related equipment                       | #TBD                                          |     |     |
| [[Lab/Consumables]]   | little thigs that require re-stocking                   | last_ordered, preferred_vendor_link, bp_rpcie |     |     |
|                       |                                                         |                                               |     |     |




