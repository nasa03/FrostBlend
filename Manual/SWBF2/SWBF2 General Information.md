![[Pasted image 20211231163936.png|512]]

## General Information

---

## Shared Groups
These groups are automatically appended when appending a main shader group that uses them.

- NormalCompleter
- NormalCombiner
- SliceCompare
- SliceProcessor
- SliceProcessor_KR
- SmoothnessCombiner
- SmoothnessCombiner_KR

---

## Slice

Slice textures are used frequently in SWBF2 to add extra detail to the materials of models.
![[Pasted image 20211231164257.png|512]]
This is an example of a slice texture. 
Each shade of grey is a seperate mask. How this is handled in the groups is through a _Mask Sample_ value. Use can colour pick an AOSL texture directly to use this. If slice is elsewhere you will need to manually input the value onto the green channel of the sample input of your choice.