# OneDrive Issue
## "the tag present in the reparse point buffer is invalid"

### Description

cannot open or edit the corresponding folder even cannot delete it.

## Solution

referecen: [Fix Onedrive The tag present in the reparse point buffer is invalid](https://www.itexperience.net/fix-onedrive-the-tag-present-in-the-reparse-point-buffer-is-invalid/)

1. open CMD as adminstrator;
2. type: `chkdsk c: /r /f`
3. type: `Y`
4. reboot

the problem should be fixed.
