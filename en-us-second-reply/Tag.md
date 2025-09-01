---

## Tag

---

---
### Writing and Overwriting Data on SwitchBot NFC Tag

When using an NFC Tag for quick control of SwitchBot products, please note that each Tag can only store one action at a time. If you write a second action to the Tag, the previous action will be automatically overwritten.

The data written to the Tag is linked to your SwitchBot account. If you write an action related to Lock or Lock Pro, such as locking or unlocking, the Tag will be automatically encrypted. If another SwitchBot account tries to write data to this encrypted Tag, an error will occur, and the process will be aborted. To remove this encryption, you must use the same account that wrote the locking/unlocking action to overwrite it with a non-Lock device action. However, if you write an action for a non-Lock device, like a Bot, the Tag can be overwritten by any account.

Once the homeowner writes an action to the Tag, other home members can simply scan the Tag to control the device.




