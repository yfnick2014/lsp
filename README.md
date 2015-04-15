# LSP
Notes for "Linux System Programming" second edition
## Center of this book
What is system-level interface, and how do I write system-level applications in Linux? What exactly do the kernel and the C library provide? How do I write optimal code, and what tricks does the Linux provide? What interesting system calls are provided in Linux compared to other Unix variants? How does it all work?
## Menu
- [Chapter 1. Introduction and Essential Concepts](content/01.md)
  - [Files and the Filesystem](content/01.md#files-and-the-filesystem)
  - [Proceses](content/01.md#proceses)
  - [Users and Groups](content/01.md#users-and-groups)
  - [Permissions](content/01.md#permissions)
  - [Signals](content/01.md#signals)
  - [Interprocess Communication](content/01.md#interprocess-communication)
- [Chapter 2. File I/O](content/02.md)
  - [Opening Files](content/02.md#opening-files)
  - [Reading via read()](content/02.md#reading-via-read)
  - [Writing with write()](content/02.md#writing-with-write)
  - [Synchronized I/O](content/02.md#synchronized-io)
  - [Direct I/O](content/02.md#direct-io)
  - [Closing Files](content/02.md#closing-files)
  - [Seeking with lseek()](content/02.md#seeking-with-lseek)
  - [Positional Reads and Writes](content/02.md#positional-reads-and-writes)
  - [Truncating Files](content/02.md#truncating-files)
  - [Mutiplexed I/O](content/02.md#mutiplexed-io)
  - [Kernel Internals](content/02.md#kernel-internals)
- [Chapter 3. Buffered I/O](content/03.md)
  - [User-Buffered I/O](content/03.md#user-buffered-io)
  - [Standard I/O](content/03.md#standard-io)
  - [Opening Files](content/03.md#opening-files)
  - [Opening a Stream via File Descriptor](content/03.md#opening-a-stream-via-file-descriptor)
  - [Closing Streams](content/03.md#closing-streams)
  - [Reading from a Stream](content/03.md#reading-from-a-stream)
  - [Writing to a Stream](content/03.md#writing-to-a-stream)
  - [Sample Program Using Buffered I/O](content/03.md#sample-program-using-buffered-io)
  - [Seeking a Stream](content/03.md#seeking-a-stream)
  - [Flushing a Stream](content/03.md#flushing-a-stream)
  - [Errors and End-of-File](content/03.md#errors-and-end-of-file)
  - [Obtaining the Associated File Descriptor](content/03.md#obtaining-the-associated-file-descriptor)
  - [Controlling the Buffering](content/03.md#controlling-the-buffering)
  - [Critiques of Standard I/O](content/03.md#critiques-of-standard-io)
- Chapter 4. Advanced File I/O
- Chapter 5. Process Management
- Chapter 6. Advanced Process Management
- Chapter 7. Threading
- Chapter 8. File and Directory Management
- Chapter 9. Memory Management
- Chapter 10. Signals
- Chapter 11. Time 