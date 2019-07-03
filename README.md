cp from my laptop: ~/dyninst4sgxminidep/dyninst-build/elfutils

actually, the main dir should be ./src, and the build dir is ./src/LibElf-build

# if we don't use libelf to analysis the elf format file, then we need a trampoline/springboard (for musl libc to invoke syscall).
