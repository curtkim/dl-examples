## intro
1. apidemo : repromath.so 을 사용. dependent library
2. lazydemo : implib를 사용. so.tramp.S, so.init.c로 동적로딩
3. pyapidemo : plugin?
4. tlsdemo : unload?


## ldd apidemo
    CMAKE_DL_LIBS 사용 

    $ ldd apidemo
        linux-vdso.so.1 (0x00007fffc73b9000)
        libdl.so.2 => /lib/x86_64-linux-gnu/libdl.so.2 (0x00007f74df3fc000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f74df20a000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f74df42a000)
