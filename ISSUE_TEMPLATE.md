<!--
	Please modify the answers below by typing "x" in between the
	parenthesis of the choices that closely relate to your issue, e.g.

		- [x] ...
-->

### Type of this issue (please specify)

- [ ] This is a bug in the upstream tree as-is unmodified.
- [ ] This is a support matter (i.e. your own modified tree)
- [ ] This is a technical question

### I hereby claim that

1) I have read the respective README sections that provide information
   regarding this and found it to be unclear/uninformative in this respective
   matter.

2) I'll provide to my best of knowledge the required information to reproduce
   and/or help improve this matter.

3) I understand and acknowledge to the best of my knowledge that this writing
   is a technical issue and is not outside the scope of this project.

### System information

1. CPU: WRITE_HERE (Codename: AND_HERE)
2. Kernel: WRITE_HERE
3. Kernel version: WRITE_HERE Build number: AND_HERE

### Build Configuration

- EPAGE_HOOK
- PMEM_SANDBOX
- ...

**REMOVE IF UNRELATED**

### Issue description

Write as much as you can, reference the files that you uploaded in the uploaded
section with their respective numbers instead of names, e.g. [1] then it refers
to #1 file in "Files" section.

### Files

Crash related files, etc, remove this text and fill the lines with something if
any, otherwise completely remove this section.

1. FILE 1 (DESC IF POSSIBLE): https://downloadlinkhere/
2. FILE 2 (DESC IF POSSIBLE): https://heregoesthedownloadlink/
3. and so on.

Please refer to each file uploaded in this section in the Issue description
part, by using [x] where x is the number of the file here.

If it's a crash you'll need to upload:

#### For Windows

- A minidump (C:\windows\minidump) or a memory dump (C:\windows\memory.dmp).  Former prefered.
- The compiled .sys and the .pdb/.dbg file
- The Kernel executable if possible, e.g. ntoskrnl.exe from C:\Windows\System32

#### For Linux

- `ksmlinux.ko` and `ksmlinux.o`
- Stack dump from dmesg or kernel panic

**REMOVE IF NOTHING PROVIDED.**

### Stack Trace

Paste stack trace text here if any.  **REMOVE IF NOTHING PROVIDED.**

### Current Behavior

Replace this body with your own, provide what the current behavior is.  **REMOVE
IF UNRELATED.**

### Expected Behavior

Replace this body with your own, provide what you're expecting.  **REMOVE IF
UNRELATED.**

### Inline code / patches to be used when reproducing

Please only use this if the code really is inline, i.e. up to 40 lines of code
here, otherwise upload a patch via the Uploaded files

**REMOVE IF NOTHING PROVIDED.**

