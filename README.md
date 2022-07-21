# sandboxie

My little experiments with sandboxing and containerization technologies. 

### The motivation behind sandboxie


I got interested in sandboxing and containerization after studying the sandboxing module from pwn.college, and out of interest I wanted to recreate those vulnerabilities and try to escape them on my own, for learning of course.

This is a work in progress, and I will keep writing about more and more sandboxing techniques and their escapes in the near future.

### Installing the Rust toolchain on GNU/ Linux based systems

I haven't tested it on Windows and I don't plan to either, if you're a Windows user, you're on your own.

```sh
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
$ rustup toolchain install stable
```


### To-do

- [ ] chroot
- [ ] cgroups
- [ ] namespaces
- [ ] bubblewrap
- [ ] seccomp

### References:

- [pwn.college sandboxing module](https://pwn.college/modules/sandbox)
- [CS695 by Mythili Vutukuru (IIT Bombay)](https://www.cse.iitb.ac.in/~mythili/virtcc/)
