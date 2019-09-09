If we use libelf to analysis the elf format file, then we may need a trampoline/springboard (for musl-libc to invoke syscall like 'read'/'pread').

The source code is in the libelf dir.
